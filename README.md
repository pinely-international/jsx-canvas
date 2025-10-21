# JSX Canvas Markup
Render your canvas elements like HTML with CSS-like styling. Supports JSX and Hyperscript markup.

## Example

With this extension `canvas` element can be put with its own subtree elements that can render elements with limited CSS support just like regular HTML.

```tsx
<div>
  <canvas>
    <c:layout style={{ display: "grid", padding: 20 }}>
      <c:text x="40" y="40" fill="#333" fontSize="16">
        Some text
      </text>
      <>
        <c:rectangle x="20" y="60" width="100" height="40" fill="#f0f" />
      </>
      <svg>
        <circle cx="150" cy="80" r="20" fill="skyblue" />
      </svg>
    </c:layout>
  </canvas>
  <button>click me</button>
</div>
```

<img width="1210" height="690" alt="image" src="https://github.com/user-attachments/assets/159860c8-734e-4fbb-bb06-252d50a0d167" />

