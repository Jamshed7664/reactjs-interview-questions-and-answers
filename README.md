<a id="top"></a>

<div align="center">

# ⚛️ Top 100 React.js Interview Questions & Answers (2026)

### Beginner → Advanced | Easy Indian English | Practical JSX Examples

**Made with ❤️ by Code with Jamshed**

[![React](https://img.shields.io/badge/React-Interview%20Preparation-149ECA?logo=react&logoColor=white)](https://react.dev/)
[![Questions](https://img.shields.io/badge/Questions-100-brightgreen)](#-questions--answers)
[![Level](https://img.shields.io/badge/Level-Beginner%20to%20Advanced-orange)](#-learning-path)
[![Markdown](https://img.shields.io/badge/Format-GitHub%20README-blue)](#-questions--answers)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-success)](#-contributing)

**⭐ If this resource helps you, please star the repository and share it with other developers.**

</div>

---

## 🎯 About this repository

Preparing for a React interview? Here you will find **100 carefully organised questions** with **simple, interview-ready answers** and **small code examples**. Explanations use easy Indian English so freshers and working professionals can revise quickly.

> **Important:** JSX snippets are focused examples; some rely on surrounding component state, imported Hooks, helper functions or a router/framework. They are **not all standalone runnable files**. Import the APIs you use (e.g. `import { useState, useEffect } from "react"`) and put Hook calls inside React components or custom Hooks.

## 🚀 Quick start

To practise examples inside a new React project:

```bash
npm create vite@latest react-interview-practice -- --template react
cd react-interview-practice
npm install
npm run dev
```

Use a supported current Node.js version and refer to [Vite documentation](https://vite.dev/guide/) for environment requirements. Paste examples into components in `src/App.jsx`, adding necessary imports and values.

## 🗺️ Learning path

| Stage | Topic | Questions |
|:--:|---|:--:|
| 1 | [React Fundamentals](#react-fundamentals) | 15 |
| 2 | [Components, Props & JSX](#components-props-jsx) | 10 |
| 3 | [State & Events](#state-events) | 15 |
| 4 | [Hooks & Effects](#hooks-effects) | 20 |
| 5 | [Routing, Forms & Data](#routing-forms-data) | 10 |
| 6 | [Performance & Advanced React](#performance-advanced-react) | 19 |
| 7 | [Practical Scenarios & Testing](#practical-scenarios-testing) | 11 |
| | **Total** | **100** |

## 📚 Questions & Answers

<details>
<summary><strong>📌 Quick question index — click to expand</strong></summary>

- [Q001. What is React?](#q001)
- [Q002. Why should we use React?](#q002)
- [Q003. What is a component?](#q003)
- [Q004. What is JSX?](#q004)
- [Q005. Is JSX mandatory?](#q005)
- [Q006. What is the difference between React and React DOM?](#q006)
- [Q007. What is the Virtual DOM?](#q007)
- [Q008. What is reconciliation?](#q008)
- [Q009. What is the difference between render and commit?](#q009)
- [Q010. What is a single-page application (SPA)?](#q010)
- [Q011. What are React fragments?](#q011)
- [Q012. How do you render conditional UI?](#q012)
- [Q013. How do you render a list?](#q013)
- [Q014. Why are keys important?](#q014)
- [Q015. What is StrictMode?](#q015)
- [Q016. What are props?](#q016)
- [Q017. Can a child modify its props?](#q017)
- [Q018. What is the children prop?](#q018)
- [Q019. How do you provide default props?](#q019)
- [Q020. What is prop drilling?](#q020)
- [Q021. What is component composition?](#q021)
- [Q022. What is a pure component?](#q022)
- [Q023. How is a function component different from a class component?](#q023)
- [Q024. How do you style React elements?](#q024)
- [Q025. How are HTML attributes different in JSX?](#q025)
- [Q026. What is state in React?](#q026)
- [Q027. What is useState?](#q027)
- [Q028. Why should state not be mutated directly?](#q028)
- [Q029. How do you update state based on previous state?](#q029)
- [Q030. Why can state appear unchanged immediately after setting it?](#q030)
- [Q031. What is batching?](#q031)
- [Q032. How do you handle click events?](#q032)
- [Q033. How do you pass arguments to an event handler?](#q033)
- [Q034. What is a controlled input?](#q034)
- [Q035. What is an uncontrolled input?](#q035)
- [Q036. How do you manage checkbox state?](#q036)
- [Q037. How do you update an array in state?](#q037)
- [Q038. How do you remove an item from state?](#q038)
- [Q039. What is lifting state up?](#q039)
- [Q040. How can you reset a child component state?](#q040)
- [Q041. What are Hooks?](#q041)
- [Q042. What are the Rules of Hooks?](#q042)
- [Q043. What does useEffect do?](#q043)
- [Q044. What is the effect dependency array?](#q044)
- [Q045. When does an effect run with no dependency array?](#q045)
- [Q046. What does [] mean in useEffect?](#q046)
- [Q047. What is effect cleanup?](#q047)
- [Q048. How do you avoid race conditions during fetch in useEffect?](#q048)
- [Q049. What is useRef?](#q049)
- [Q050. How do you focus an input with useRef?](#q050)
- [Q051. What is useMemo?](#q051)
- [Q052. What is useCallback?](#q052)
- [Q053. What is the difference between useMemo and useCallback?](#q053)
- [Q054. What is useReducer?](#q054)
- [Q055. When should you use useReducer instead of useState?](#q055)
- [Q056. What is useContext?](#q056)
- [Q057. How do you create and provide context?](#q057)
- [Q058. What is a custom Hook?](#q058)
- [Q059. What is useLayoutEffect?](#q059)
- [Q060. What is useId?](#q060)
- [Q061. How is routing handled in a React app?](#q061)
- [Q062. How do you navigate without a full reload?](#q062)
- [Q063. What is a route parameter?](#q063)
- [Q064. What is lazy loading in React?](#q064)
- [Q065. What does Suspense do?](#q065)
- [Q066. How do you validate a React form?](#q066)
- [Q067. How do you prevent a form from refreshing the page?](#q067)
- [Q068. How do you fetch API data in React?](#q068)
- [Q069. What are loading and error states?](#q069)
- [Q070. What is an error boundary?](#q070)
- [Q071. What is React.memo?](#q071)
- [Q072. Why can React.memo still re-render?](#q072)
- [Q073. What is code splitting?](#q073)
- [Q074. What is useTransition?](#q074)
- [Q075. What is useDeferredValue?](#q075)
- [Q076. What is hydration?](#q076)
- [Q077. What is SSR?](#q077)
- [Q078. What is CSR?](#q078)
- [Q079. What are portals?](#q079)
- [Q080. What is an imperative handle?](#q080)
- [Q081. What are React Server Components?](#q081)
- [Q082. What does "use client" mean?](#q082)
- [Q083. What is useActionState?](#q083)
- [Q084. What is useOptimistic?](#q084)
- [Q085. What does the use API do in React?](#q085)
- [Q086. Can function components accept ref directly?](#q086)
- [Q087. What is React Compiler?](#q087)
- [Q088. How do you prevent unnecessary re-renders?](#q088)
- [Q089. How do you debug performance issues?](#q089)
- [Q090. How do you test a React component?](#q090)
- [Q091. What is the difference between unit and integration tests?](#q091)
- [Q092. How do you test a button click?](#q092)
- [Q093. How do you implement debounced search?](#q093)
- [Q094. How do you create a reusable modal?](#q094)
- [Q095. How do you handle empty search results?](#q095)
- [Q096. How do you implement pagination?](#q096)
- [Q097. How do you avoid XSS in React?](#q097)
- [Q098. Why should you not put secrets in frontend environment variables?](#q098)
- [Q099. What is accessibility in React?](#q099)
- [Q100. How do you structure a large React app?](#q100)

</details>

---


## React Fundamentals

<a id="q001"></a>

### 1. What is React?

**✅ Easy Answer:** React is a JavaScript library for building interactive UIs using reusable components. React updates the UI when data changes.

**💻 Example:**

```jsx
function App() { return <h1>Hello React</h1>; }
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q002"></a>

### 2. Why should we use React?

**✅ Easy Answer:** It makes complex UI easier to split into reusable components and keeps UI in sync with state.

**💻 Example:**

```jsx
function Badge({ text }) { return <span>{text}</span>; }
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q003"></a>

### 3. What is a component?

**✅ Easy Answer:** A component is a reusable function that returns React elements, usually written with JSX.

**💻 Example:**

```jsx
function Welcome() { return <h2>Welcome!</h2>; }
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q004"></a>

### 4. What is JSX?

**✅ Easy Answer:** JSX lets you write HTML-like markup inside JavaScript. Build tools transform it into JavaScript.

**💻 Example:**

```jsx
const heading = <h1>Hi, Jamshed!</h1>;
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q005"></a>

### 5. Is JSX mandatory?

**✅ Easy Answer:** No. JSX is convenient, but React elements can also be created without JSX.

**💻 Example:**

```jsx
import { createElement } from "react";
const title = createElement("h1", null, "Hello");
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q006"></a>

### 6. What is the difference between React and React DOM?

**✅ Easy Answer:** react contains component and Hook APIs; react-dom handles integration with browser DOM.

**💻 Example:**

```jsx
import { createRoot } from "react-dom/client";
createRoot(document.getElementById("root")).render(<App />);
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q007"></a>

### 7. What is the Virtual DOM?

**✅ Easy Answer:** It is a common term for React’s in-memory UI representation. React compares renders and commits necessary DOM changes; it is not a second browser DOM.

**💻 Example:**

```jsx
const element = <p>Count: 1</p>;
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q008"></a>

### 8. What is reconciliation?

**✅ Easy Answer:** React matches the previous and next element trees to decide what to preserve, update or recreate. Type and key matter.

**💻 Example:**

```jsx
items.map(item => <li key={item.id}>{item.name}</li>);
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q009"></a>

### 9. What is the difference between render and commit?

**✅ Easy Answer:** Render calculates what UI should look like; commit applies needed changes to the DOM.

**💻 Example:**

```jsx
function Counter({ count }) { return <p>{count}</p>; }
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q010"></a>

### 10. What is a single-page application (SPA)?

**✅ Easy Answer:** An SPA usually loads one HTML shell and changes views in the browser without full document navigation on every route. React can also be used outside SPAs.

**💻 Example:**

```jsx
function App() { return <main><h1>Dashboard</h1></main>; }
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q011"></a>

### 11. What are React fragments?

**✅ Easy Answer:** Fragments group elements without adding an extra DOM element.

**💻 Example:**

```jsx
return <><h1>Title</h1><p>Details</p></>;
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q012"></a>

### 12. How do you render conditional UI?

**✅ Easy Answer:** Use normal JavaScript conditions such as ternary or && inside JSX.

**💻 Example:**

```jsx
return isLoggedIn ? <Dashboard /> : <Login />;
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q013"></a>

### 13. How do you render a list?

**✅ Easy Answer:** Use map() to convert data into elements. Provide stable keys for siblings.

**💻 Example:**

```jsx
const names = ["Asha", "Ravi"];
return <ul>{names.map(n => <li key={n}>{n}</li>)}</ul>;
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q014"></a>

### 14. Why are keys important?

**✅ Easy Answer:** Keys help React identify list items across inserts, deletions and reorderings. Prefer stable IDs instead of array indexes for changing lists.

**💻 Example:**

```jsx
todos.map(todo => <Todo key={todo.id} todo={todo} />);
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q015"></a>

### 15. What is StrictMode?

**✅ Easy Answer:** StrictMode enables extra checks in development. It can re-render components and re-run effects to reveal bugs; these checks are not production behaviour.

**💻 Example:**

```jsx
import { StrictMode } from "react";
root.render(<StrictMode><App /></StrictMode>);
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---


## Components, Props & JSX

<a id="q016"></a>

### 16. What are props?

**✅ Easy Answer:** Props are read-only inputs that a parent passes to a child component.

**💻 Example:**

```jsx
function Greeting({ name }) { return <h1>Hi {name}</h1>; }
// <Greeting name="Jamshed" />
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q017"></a>

### 17. Can a child modify its props?

**✅ Easy Answer:** No. Treat props as immutable. Ask the parent to update state through a callback instead.

**💻 Example:**

```jsx
function Child({ onChange }) { return <button onClick={() => onChange("new")}>Update</button>; }
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q018"></a>

### 18. What is the children prop?

**✅ Easy Answer:** children represents nested content passed between a component’s opening and closing tags.

**💻 Example:**

```jsx
function Card({ children }) { return <section>{children}</section>; }
// <Card><p>Hello</p></Card>
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q019"></a>

### 19. How do you provide default props?

**✅ Easy Answer:** For modern function components, use JavaScript default parameters while destructuring.

**💻 Example:**

```jsx
function Avatar({ size = 48 }) { return <img width={size} alt="User" src="/avatar.png" />; }
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q020"></a>

### 20. What is prop drilling?

**✅ Easy Answer:** It means forwarding props through many intermediate components. Composition or context may help when the passing becomes difficult.

**💻 Example:**

```jsx
function Layout({ user }) { return <Header user={user} />; }
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q021"></a>

### 21. What is component composition?

**✅ Easy Answer:** Composition combines small components by nesting or passing elements instead of building huge components.

**💻 Example:**

```jsx
function Panel({ children }) { return <div className="panel">{children}</div>; }
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q022"></a>

### 22. What is a pure component?

**✅ Easy Answer:** Given the same props, state and context, its render should produce the same result without side effects.

**💻 Example:**

```jsx
function Total({ price, qty }) { return <strong>{price * qty}</strong>; }
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q023"></a>

### 23. How is a function component different from a class component?

**✅ Easy Answer:** Function components use Hooks and are preferred for new code. Class components use lifecycle methods and this.state.

**💻 Example:**

```jsx
function Hello() { return <p>Hello</p>; }
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q024"></a>

### 24. How do you style React elements?

**✅ Easy Answer:** Use className for CSS classes or style with a JavaScript object.

**💻 Example:**

```jsx
return <p className="message" style={{ color: "teal" }}>Hi</p>;
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q025"></a>

### 25. How are HTML attributes different in JSX?

**✅ Easy Answer:** Many attributes use camelCase names; class becomes className and htmlFor replaces for.

**💻 Example:**

```jsx
return <label htmlFor="email">Email<input id="email" /></label>;
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---


## State & Events

<a id="q026"></a>

### 26. What is state in React?

**✅ Easy Answer:** State stores information a component remembers between renders. Updating it requests a new render.

**💻 Example:**

```jsx
const [count, setCount] = useState(0);
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q027"></a>

### 27. What is useState?

**✅ Easy Answer:** useState returns the current value and setter. Import it from react in your component.

**💻 Example:**

```jsx
import { useState } from "react";
const [name, setName] = useState("Jamshed");
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q028"></a>

### 28. Why should state not be mutated directly?

**✅ Easy Answer:** React expects a new value/reference to detect updates. Mutating existing objects can lead to stale UI.

**💻 Example:**

```jsx
setUser(prev => ({ ...prev, city: "Lucknow" }));
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q029"></a>

### 29. How do you update state based on previous state?

**✅ Easy Answer:** Use the functional setter so queued updates work correctly.

**💻 Example:**

```jsx
setCount(c => c + 1);
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q030"></a>

### 30. Why can state appear unchanged immediately after setting it?

**✅ Easy Answer:** A setter schedules a render; the current handler still sees values from its existing render snapshot.

**💻 Example:**

```jsx
setCount(c => c + 1); // read updated value on next render
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q031"></a>

### 31. What is batching?

**✅ Easy Answer:** React groups multiple state updates to reduce unnecessary renders. Use functional updates when each update depends on the last.

**💻 Example:**

```jsx
setCount(c => c + 1);
setCount(c => c + 1); // increases by 2
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q032"></a>

### 32. How do you handle click events?

**✅ Easy Answer:** Pass a function to onClick; do not call it while rendering.

**💻 Example:**

```jsx
return <button onClick={() => alert("Clicked!")}>Click</button>;
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q033"></a>

### 33. How do you pass arguments to an event handler?

**✅ Easy Answer:** Wrap the call in an arrow function.

**💻 Example:**

```jsx
return <button onClick={() => removeItem(id)}>Remove</button>;
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q034"></a>

### 34. What is a controlled input?

**✅ Easy Answer:** An input whose value comes from React state and whose onChange updates that state.

**💻 Example:**

```jsx
const [name, setName] = useState("");
return <input value={name} onChange={e => setName(e.target.value)} />;
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q035"></a>

### 35. What is an uncontrolled input?

**✅ Easy Answer:** The DOM stores the input value. You can read it using a ref when needed.

**💻 Example:**

```jsx
const inputRef = useRef(null);
return <input ref={inputRef} defaultValue="Hello" />;
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q036"></a>

### 36. How do you manage checkbox state?

**✅ Easy Answer:** Store a boolean and bind checked plus onChange.

**💻 Example:**

```jsx
const [ok, setOk] = useState(false);
return <input type="checkbox" checked={ok} onChange={e => setOk(e.target.checked)} />;
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q037"></a>

### 37. How do you update an array in state?

**✅ Easy Answer:** Create a new array with map, filter or spread instead of push/splice on current state.

**💻 Example:**

```jsx
setTodos(prev => [...prev, { id: 3, text: "Learn" }]);
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q038"></a>

### 38. How do you remove an item from state?

**✅ Easy Answer:** Filter the existing array and return a new one.

**💻 Example:**

```jsx
setTodos(prev => prev.filter(t => t.id !== removeId));
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q039"></a>

### 39. What is lifting state up?

**✅ Easy Answer:** Move shared state to the closest common parent so sibling components remain in sync.

**💻 Example:**

```jsx
function Parent() { const [value, setValue] = useState(""); return <><Input value={value} onChange={setValue} /><Preview value={value} /></>; }
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q040"></a>

### 40. How can you reset a child component state?

**✅ Easy Answer:** Changing its key makes React create a fresh component instance. Use intentionally.

**💻 Example:**

```jsx
return <Profile key={userId} userId={userId} />;
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---


## Hooks & Effects

<a id="q041"></a>

### 41. What are Hooks?

**✅ Easy Answer:** Hooks are React functions that let function components use state, effects, context and other features.

**💻 Example:**

```jsx
import { useState, useEffect } from "react";
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q042"></a>

### 42. What are the Rules of Hooks?

**✅ Easy Answer:** Call Hooks at the top level of React components or custom Hooks, not inside loops, conditions or event handlers.

**💻 Example:**

```jsx
function App() { const [open] = useState(false); return <p>{String(open)}</p>; }
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q043"></a>

### 43. What does useEffect do?

**✅ Easy Answer:** It synchronizes a component with an external system such as a timer, subscription or network connection.

**💻 Example:**

```jsx
useEffect(() => { document.title = "Dashboard"; }, []);
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q044"></a>

### 44. What is the effect dependency array?

**✅ Easy Answer:** It tells React which reactive values an effect uses, so it re-runs when those values change.

**💻 Example:**

```jsx
useEffect(() => { document.title = `Hello ${name}`; }, [name]);
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q045"></a>

### 45. When does an effect run with no dependency array?

**✅ Easy Answer:** After every committed render, when the effect is enabled. Avoid this unless it is needed.

**💻 Example:**

```jsx
useEffect(() => { console.log("After render"); });
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q046"></a>

### 46. What does [] mean in useEffect?

**✅ Easy Answer:** The effect does not re-run due to changed dependencies, but development StrictMode may run an extra setup/cleanup cycle.

**💻 Example:**

```jsx
useEffect(() => { console.log("setup"); return () => console.log("cleanup"); }, []);
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q047"></a>

### 47. What is effect cleanup?

**✅ Easy Answer:** A returned function removes a subscription, clears timers or cancels work when dependencies change or a component unmounts.

**💻 Example:**

```jsx
useEffect(() => { const id = setInterval(tick, 1000); return () => clearInterval(id); }, []);
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q048"></a>

### 48. How do you avoid race conditions during fetch in useEffect?

**✅ Easy Answer:** Abort stale requests and ignore abort errors so old responses do not overwrite newer state.

**💻 Example:**

```jsx
useEffect(() => { const c = new AbortController(); fetch(`/api/users/${id}`, { signal: c.signal }).then(r => r.json()).then(setUser).catch(e => { if (e.name !== "AbortError") console.error(e); }); return () => c.abort(); }, [id]);
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q049"></a>

### 49. What is useRef?

**✅ Easy Answer:** It stores a mutable value that survives renders without triggering re-renders. It also holds DOM references.

**💻 Example:**

```jsx
const inputRef = useRef(null);
return <input ref={inputRef} />;
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q050"></a>

### 50. How do you focus an input with useRef?

**✅ Easy Answer:** Attach the ref, then access the DOM element from an event handler or effect.

**💻 Example:**

```jsx
const ref = useRef(null);
return <><input ref={ref} /><button onClick={() => ref.current?.focus()}>Focus</button></>;
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q051"></a>

### 51. What is useMemo?

**✅ Easy Answer:** It caches the result of a calculation between renders when dependencies are unchanged. Use when work is expensive.

**💻 Example:**

```jsx
const total = useMemo(() => items.reduce((s, x) => s + x.price, 0), [items]);
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q052"></a>

### 52. What is useCallback?

**✅ Easy Answer:** It caches a function reference between renders; useful for optimized children or stable dependencies.

**💻 Example:**

```jsx
const handleSave = useCallback(() => save(id), [id]);
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q053"></a>

### 53. What is the difference between useMemo and useCallback?

**✅ Easy Answer:** useMemo caches a computed value, while useCallback caches a function definition.

**💻 Example:**

```jsx
const doubled = useMemo(() => n * 2, [n]);
const double = useCallback(() => n * 2, [n]);
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q054"></a>

### 54. What is useReducer?

**✅ Easy Answer:** It manages state using a reducer function and dispatch actions; useful for more complex update logic.

**💻 Example:**

```jsx
function reducer(state, action) { return action.type === "inc" ? state + 1 : state; }
const [count, dispatch] = useReducer(reducer, 0);
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q055"></a>

### 55. When should you use useReducer instead of useState?

**✅ Easy Answer:** Choose useReducer when many related updates or action types make state logic hard to follow.

**💻 Example:**

```jsx
dispatch({ type: "inc" });
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q056"></a>

### 56. What is useContext?

**✅ Easy Answer:** It reads the closest value provided by a matching Context Provider without manually passing props through every level.

**💻 Example:**

```jsx
const theme = useContext(ThemeContext);
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q057"></a>

### 57. How do you create and provide context?

**✅ Easy Answer:** Create a context and wrap children with its provider; consumers use useContext.

**💻 Example:**

```jsx
const ThemeContext = createContext("light");
// <ThemeContext.Provider value="dark"><App /></ThemeContext.Provider>
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q058"></a>

### 58. What is a custom Hook?

**✅ Easy Answer:** A reusable function starting with use that can call other Hooks and share logic (not state instances automatically).

**💻 Example:**

```jsx
function useToggle() { const [on, setOn] = useState(false); return [on, () => setOn(v => !v)]; }
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q059"></a>

### 59. What is useLayoutEffect?

**✅ Easy Answer:** It works like useEffect but runs before the browser repaints after a commit. Reserve it for layout measurement/visual synchronization.

**💻 Example:**

```jsx
useLayoutEffect(() => { const width = ref.current?.getBoundingClientRect().width; console.log(width); }, []);
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q060"></a>

### 60. What is useId?

**✅ Easy Answer:** It generates stable unique IDs for accessibility relationships, not for list keys.

**💻 Example:**

```jsx
const id = useId();
return <><label htmlFor={id}>Email</label><input id={id} /></>;
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---


## Routing, Forms & Data

<a id="q061"></a>

### 61. How is routing handled in a React app?

**✅ Easy Answer:** Use a router library or framework to map URLs to UI. React itself does not ship an app router.

**💻 Example:**

```jsx
// React Router (example)
<Routes><Route path="/about" element={<About />} /></Routes>
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q062"></a>

### 62. How do you navigate without a full reload?

**✅ Easy Answer:** A client-side router usually provides Link components and navigation APIs.

**💻 Example:**

```jsx
// React Router
<Link to="/dashboard">Dashboard</Link>
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q063"></a>

### 63. What is a route parameter?

**✅ Easy Answer:** A dynamic part of the URL, such as /users/42, that the router makes available to the page.

**💻 Example:**

```jsx
// React Router
const { userId } = useParams();
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q064"></a>

### 64. What is lazy loading in React?

**✅ Easy Answer:** You can load component code when needed using lazy and render a fallback with Suspense.

**💻 Example:**

```jsx
const Settings = lazy(() => import("./Settings"));
return <Suspense fallback={<p>Loading...</p>}><Settings /></Suspense>;
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q065"></a>

### 65. What does Suspense do?

**✅ Easy Answer:** Suspense shows fallback UI while a supported descendant is loading or suspending. It does not automatically make arbitrary useEffect fetches suspend.

**💻 Example:**

```jsx
<Suspense fallback={<Spinner />}><LazyPage /></Suspense>
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q066"></a>

### 66. How do you validate a React form?

**✅ Easy Answer:** Check values before submission or use a form library/schema validator for larger forms.

**💻 Example:**

```jsx
function submit(e) { e.preventDefault(); if (!email.includes("@")) return setError("Enter valid email"); }
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q067"></a>

### 67. How do you prevent a form from refreshing the page?

**✅ Easy Answer:** Handle onSubmit and call preventDefault for client-managed forms.

**💻 Example:**

```jsx
return <form onSubmit={e => { e.preventDefault(); save(); }}><button>Save</button></form>;
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q068"></a>

### 68. How do you fetch API data in React?

**✅ Easy Answer:** Use framework data APIs, a fetching library, or an effect with loading, error, and cleanup handling.

**💻 Example:**

```jsx
useEffect(() => { const c = new AbortController(); fetch("/api/items", { signal: c.signal }).then(r => { if (!r.ok) throw Error("HTTP error"); return r.json(); }).then(setItems).catch(e => { if (e.name !== "AbortError") setError(e.message); }); return () => c.abort(); }, []);
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q069"></a>

### 69. What are loading and error states?

**✅ Easy Answer:** They make asynchronous UI clear: show a spinner while waiting, an error on failure, and data on success.

**💻 Example:**

```jsx
if (error) return <p>{error}</p>;
if (loading) return <p>Loading...</p>;
return <List items={items} />;
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q070"></a>

### 70. What is an error boundary?

**✅ Easy Answer:** A class component (or a library helper) that catches rendering errors below it and displays fallback UI. It does not catch ordinary event-handler errors.

**💻 Example:**

```jsx
class Boundary extends React.Component { state = { failed: false }; static getDerivedStateFromError() { return { failed: true }; } render() { return this.state.failed ? <p>Something went wrong</p> : this.props.children; } }
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---


## Performance & Advanced React

<a id="q071"></a>

### 71. What is React.memo?

**✅ Easy Answer:** It can skip re-rendering when props are unchanged. It is an optimization, not a correctness tool.

**💻 Example:**

```jsx
const Row = memo(function Row({ title }) { return <li>{title}</li>; });
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q072"></a>

### 72. Why can React.memo still re-render?

**✅ Easy Answer:** A memoized component can re-render when its own state or context changes; changed prop references also invalidate memoization.

**💻 Example:**

```jsx
const options = useMemo(() => ({ page }), [page]);
return <MemoizedTable options={options} />;
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q073"></a>

### 73. What is code splitting?

**✅ Easy Answer:** It breaks application JavaScript into chunks so users download only code needed for a view or feature.

**💻 Example:**

```jsx
const Reports = lazy(() => import("./Reports"));
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q074"></a>

### 74. What is useTransition?

**✅ Easy Answer:** It marks some state updates as non-blocking transitions, keeping urgent input updates responsive.

**💻 Example:**

```jsx
const [pending, startTransition] = useTransition();
startTransition(() => setTab(nextTab));
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q075"></a>

### 75. What is useDeferredValue?

**✅ Easy Answer:** It lets a less-urgent part of the UI lag behind fast-changing values for responsiveness.

**💻 Example:**

```jsx
const deferredQuery = useDeferredValue(query);
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q076"></a>

### 76. What is hydration?

**✅ Easy Answer:** Hydration attaches client-side React behaviour to HTML generated on the server. The initial markup should match.

**💻 Example:**

```jsx
import { hydrateRoot } from "react-dom/client";
hydrateRoot(document.getElementById("root"), <App />);
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q077"></a>

### 77. What is SSR?

**✅ Easy Answer:** Server-side rendering creates HTML on a server for an initial request; the browser can later hydrate interactive portions.

**💻 Example:**

```jsx
// Conceptual: a framework can render a page on the server.
function Page() { return <h1>Product</h1>; }
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q078"></a>

### 78. What is CSR?

**✅ Easy Answer:** Client-side rendering builds the UI in the browser after JavaScript loads.

**💻 Example:**

```jsx
createRoot(document.getElementById("root")).render(<App />);
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q079"></a>

### 79. What are portals?

**✅ Easy Answer:** Portals render children into another DOM node while retaining their place in the React tree. Useful for modals.

**💻 Example:**

```jsx
import { createPortal } from "react-dom";
return createPortal(<div role="dialog">Hello</div>, document.body);
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q080"></a>

### 80. What is an imperative handle?

**✅ Easy Answer:** It exposes a controlled imperative API through a ref rather than exposing all internal implementation details.

**💻 Example:**

```jsx
function Field({ ref }) { const inner = useRef(null); useImperativeHandle(ref, () => ({ focus: () => inner.current?.focus() }), []); return <input ref={inner} />; } // React 19+
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q081"></a>

### 81. What are React Server Components?

**✅ Easy Answer:** Server Components render in a server environment and can access server data. Interactive client components are separated by the framework’s client boundary.

**💻 Example:**

```jsx
// Framework-dependent server component
async function Page() { const posts = await getPosts(); return <PostList posts={posts} />; }
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q082"></a>

### 82. What does "use client" mean?

**✅ Easy Answer:** In frameworks supporting React Server Components, it declares a client entry boundary for interactive components. It is not a general browser-only instruction in plain Vite apps.

**💻 Example:**

```jsx
"use client";
import { useState } from "react";
export default function Button() { const [n, setN] = useState(0); return <button onClick={() => setN(n + 1)}>{n}</button>; }
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q083"></a>

### 83. What is useActionState?

**✅ Easy Answer:** It manages state for an action and provides a pending flag; useful for forms and action results in React 19+.

**💻 Example:**

```jsx
const [message, action, pending] = useActionState(async (_prev, formData) => `Saved ${formData.get("name")}`, "");
// <form action={action}><input name="name"/><button disabled={pending}>Save</button></form>
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q084"></a>

### 84. What is useOptimistic?

**✅ Easy Answer:** It displays an optimistic state immediately while an action is pending, and later reconciles with actual data.

**💻 Example:**

```jsx
const [optimisticLikes, addOptimisticLike] = useOptimistic(likes, (current, delta) => current + delta);
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q085"></a>

### 85. What does the use API do in React?

**✅ Easy Answer:** React 19 use(resource) can read supported promises or context during rendering, integrating with Suspense. Promise handling needs a compatible data source/framework.

**💻 Example:**

```jsx
import { use } from "react";
function Message({ messagePromise }) { const message = use(messagePromise); return <p>{message}</p>; }
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q086"></a>

### 86. Can function components accept ref directly?

**✅ Easy Answer:** In React 19+, ref can be received as a regular prop by function components. Older React code commonly used forwardRef.

**💻 Example:**

```jsx
function MyInput({ ref }) { return <input ref={ref} />; }
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q087"></a>

### 87. What is React Compiler?

**✅ Easy Answer:** React Compiler is an optimization tool that can automatically memoize eligible components and values; it does not replace good state design.

**💻 Example:**

```jsx
// Normal, pure component code benefits from compiler optimization.
function Price({ amount }) { return <p>{amount * 1.18}</p>; }
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q088"></a>

### 88. How do you prevent unnecessary re-renders?

**✅ Easy Answer:** Keep state local, remove unnecessary Effects, use stable keys and composition; profile before adding memoization.

**💻 Example:**

```jsx
const filtered = useMemo(() => expensiveFilter(items, query), [items, query]);
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q089"></a>

### 89. How do you debug performance issues?

**✅ Easy Answer:** Use React Developer Tools Profiler and browser performance tools to find expensive renders and interactions before optimising.

**💻 Example:**

```jsx
// Example optimisation after profiling
const HeavyList = memo(function HeavyList({ items }) { return <List items={items} />; });
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---


## Practical Scenarios & Testing

<a id="q090"></a>

### 90. How do you test a React component?

**✅ Easy Answer:** Use React Testing Library to render a component and verify what a user can see or do.

**💻 Example:**

```jsx
render(<Greeting name="Jamshed" />);
expect(screen.getByText("Hi Jamshed")).toBeInTheDocument();
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q091"></a>

### 91. What is the difference between unit and integration tests?

**✅ Easy Answer:** Unit tests check small behaviours; integration tests check several parts working together.

**💻 Example:**

```jsx
// Integration idea: render LoginForm, enter details and verify success UI.
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q092"></a>

### 92. How do you test a button click?

**✅ Easy Answer:** Use user-event to simulate realistic user interaction and assert the result.

**💻 Example:**

```jsx
const user = userEvent.setup();
await user.click(screen.getByRole("button", { name: /save/i }));
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q093"></a>

### 93. How do you implement debounced search?

**✅ Easy Answer:** Delay a search until typing pauses, and clear the previous timeout during cleanup.

**💻 Example:**

```jsx
useEffect(() => { const t = setTimeout(() => setDebounced(query), 300); return () => clearTimeout(t); }, [query]);
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q094"></a>

### 94. How do you create a reusable modal?

**✅ Easy Answer:** Build a component that accepts open, onClose and children; for accessibility manage focus, Escape, and dialog semantics.

**💻 Example:**

```jsx
function Modal({ open, children }) { return open ? createPortal(<div role="dialog" aria-modal="true">{children}</div>, document.body) : null; }
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q095"></a>

### 95. How do you handle empty search results?

**✅ Easy Answer:** Check the filtered list length and show a helpful empty message instead of a blank area.

**💻 Example:**

```jsx
return filtered.length ? <Results items={filtered} /> : <p>No results found.</p>;
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q096"></a>

### 96. How do you implement pagination?

**✅ Easy Answer:** Store the current page and render a slice; for server data, request one page at a time.

**💻 Example:**

```jsx
const pageItems = items.slice((page - 1) * 10, page * 10);
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

<a id="q097"></a>

### 97. How do you avoid XSS in React?

**✅ Easy Answer:** Render untrusted strings as JSX text, which React escapes. Avoid dangerouslySetInnerHTML unless HTML is trusted and sanitised.

**💻 Example:**

```jsx
return <p>{userProvidedText}</p>; // text is escaped
```

**🎤 Interview tip:** Explain the idea first, then walk through what the example is doing.

[⬆ Back to top](#top)

---

<a id="q098"></a>

### 98. Why should you not put secrets in frontend environment variables?

**✅ Easy Answer:** Frontend bundles are visible to users. Keep private API keys and credentials on your server.

**💻 Example:**

```jsx
// Good: frontend calls your backend
fetch("/api/profile");
```

**🎤 Interview tip:** Mention one practical use case instead of memorising only a definition.

[⬆ Back to top](#top)

---

<a id="q099"></a>

### 99. What is accessibility in React?

**✅ Easy Answer:** Build UIs that work with keyboards, screen readers and assistive tools using semantic HTML and proper labels.

**💻 Example:**

```jsx
return <button type="button" aria-label="Close menu" onClick={onClose}>×</button>;
```

**🎤 Interview tip:** In an interview, point out the main rule and one common mistake.

[⬆ Back to top](#top)

---

<a id="q100"></a>

### 100. How do you structure a large React app?

**✅ Easy Answer:** Group code by feature, separate reusable UI and API logic, and keep dependencies clear. Avoid overengineering small apps.

**💻 Example:**

```jsx
// src/features/auth/LoginForm.jsx
// src/features/products/ProductList.jsx
```

**🎤 Interview tip:** Be ready to explain why this approach is useful in a real project.

[⬆ Back to top](#top)

---

## 💡 Interview preparation tips

1. Understand the **why** behind each concept before memorising the answer.
2. Type the examples yourself, then change a value and predict the result.
3. Practise explaining an answer in **30–60 seconds** using your own words.
4. Build a mini project: counter, todo list, API search, login form and routed dashboard.
5. Review React's official docs whenever framework behaviour or APIs change.

## 🔗 Official references

- [React Learn](https://react.dev/learn)
- [React API Reference](https://react.dev/reference/react)
- [React Hooks Reference](https://react.dev/reference/react/hooks)
- [React 19 announcement](https://react.dev/blog/2024/12/05/react-19)
- [React Router](https://reactrouter.com/)
- [React DevTools](https://react.dev/learn/react-developer-tools)

## 🤝 Contributing

Found a typo or an incorrect snippet? Open an issue with the question number or send a pull request with a clear explanation. Please keep answers beginner-friendly, technically accurate and original.

## 📣 Support

If this guide helps, **⭐ star your repository**, share it with your study group, and use it for revision. Contributions and corrections are always welcome.

---

<div align="center">

**Code with Jamshed • Learn • Build • Share**

*Educational content. React is a trademark of Meta Platforms, Inc. This repository is not affiliated with React or Meta.*

</div>
