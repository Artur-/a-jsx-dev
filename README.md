JSX dev transform for React 19 that includes the removed `_debugSource`
information that refers to the source location where an JSX element is
instantiated in React 18.

Abuses the React 19 `_debugInfo` property to make the source location
available.
