# React Quick Revision Cheat Sheet

## JSX & Rendering
- Write UI with JSX (looks like HTML).
- Use {} for embedding JS expressions.
- Lists require unique 'key' prop.
- Conditional rendering: {condition && <Component />} or {condition ? A : B}.

## Components
- Functional components are the standard.
- Pass data via props.
- Compose components (nest them).

## State Management (Hooks)
- useState: local state.
- useEffect: side effects (API calls, subscriptions).
- useRef: store mutable values, DOM refs.
- useContext: simple global state.

## Events & Forms
- Events: onClick, onChange, etc.
- Controlled inputs: value + onChange tied to state.
- Forms: preventDefault() on submit.

## Routing (react-router-dom)
- <BrowserRouter>, <Routes>, <Route>.
- Link for navigation.
- useNavigate for programmatic routing.

## Data Fetching
- Fetch data in useEffect.
- Track loading & error state.
- Cleanup with abort controller if needed.

## Performance
- React.memo: prevent unnecessary renders.
- useCallback: memoize functions.
- useMemo: memoize values.

## Styling
- Inline styles: style={{color:'red'}}.
- CSS Modules or Tailwind recommended.

