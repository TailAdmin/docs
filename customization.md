---
description: >-
  In this part of the documentation, we are going to show you how you can
  customize the tailwind.config.js file.
---

# 💅 Customization

You can add your personalized styling by customizing the config file. You can customize things like **Colors, Screens, Spacing**, and many more.

### **Colors**:

To customize colors,, all you have to do is add the custom color values inside the color key. This way you can add custom colors for your project.

```jsx
module.exports = {
  theme: {
    colors: {
      transparent: 'transparent',
      black: '#000',
      white: '#fff',
      gray: {
        100: '#f7fafc',
        // ...
        900: '#1a202c',
      },

      // ...
    }
  }
}
```

### **Spacing**:

Just like the colors you can customize spacing by adding the values to the spacing key.

**Note:** The spacing values are inherited by **padding, margin, width, height, maxHeight,** and the rest of the pacing properties.

```jsx
module.exports = {
  theme: {
    spacing: {
      px: '1px',
			px2: '2px',
      0: '0',
      0.5: '0.125rem'
			// ...
    },
  }
}
```

### Screen:

You can add custom breakpoints by adding the custom values to the **screen** key.

```jsx
module.exports = {
  theme: {
		screens: {
        '3xl': '1600px',
				'4xl': '2000px',
				 // ...
     }
  },
};
```

This is how you can add custom styling to your Tailwind CSS project. If you want to learn more and customize other things like font family, opacity, etc, check out the [Tailwind CSS documentation](https://tailwindcss.com/docs/configuration).
