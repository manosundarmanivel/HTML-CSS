
### **1. `.modal {}` (Backdrop/Overlay)**
- Covers the whole screen.
- Uses `display: none;` to **hide modal by default**.
- When `:target` is activated, it becomes visible.

### **2. `:target {}` (Show Modal on Click)**
- When URL contains `#modal`, it **activates the modal** by changing `display: flex;`.

### **3. `.modal-content {}` (Modal Box)**
- Styled with `background: white;` for a clean design.
- Uses `position: relative;` so the close button positions correctly.
- Rounded corners and box-shadow for a **modern look**.

### **4. `.close-btn {}` (Close Button)**
- Positioned using `absolute` inside `.modal-content`.
- Clicking this link removes `#modal` from the URL, **hiding the modal**.


## Desktop Preview
![Portfolio Website Preview](assets/desktop-View.png)
