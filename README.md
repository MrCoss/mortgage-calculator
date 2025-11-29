# Mortgage Calculator
<img width="1921" height="1386" alt="image" src="https://github.com/user-attachments/assets/d58b57c4-2c5d-4c50-aa14-666a56e72b3d" />

A responsive and user-friendly **Mortgage Calculator** built with **HTML, CSS, and JavaScript**, designed to help users estimate monthly mortgage payments accurately and intuitively. This project was developed as part of the **Lloyds Banking Group Digital Redesign Challenge**, focusing on delivering a clean UI, accurate financial logic, and robust usability testing.

---

## Overview

The **Mortgage Calculator** allows users to quickly evaluate their potential mortgage repayments by entering key loan details such as **loan amount**, **interest rate**, and **loan term**. The tool provides an instant breakdown of **monthly payments**, **total interest**, and **overall repayment**, making it an ideal financial planning aid.

The solution emphasizes **clarity, accessibility, and precision**, ensuring customers can make informed mortgage decisions effortlessly.

---

## Features

* **Dynamic Calculations:** Real-time computation of monthly EMI, total payment, and total interest.
* **Responsive Design:** Works seamlessly across desktops, tablets, and smartphones.
* **Interactive Controls:**

  * Slider for interest rate adjustment
  * Dropdown menus for loan term and mortgage type
* **Error Handling:** Gracefully manages invalid or missing inputs with contextual alerts.
* **Modern UI:** Corporate-themed interface with smooth gradients, subtle animations, and professional typography.
* **Extensible Architecture:** Can integrate with backend APIs or Azure Functions for analytics or dynamic rate updates.
* **Cross-Browser Compatibility:** Optimized for Chrome, Edge, and Firefox.

---

## Tech Stack

| Layer                 | Technology                                               |
| --------------------- | -------------------------------------------------------- |
| **Frontend**          | HTML5, CSS3, JavaScript (Vanilla JS)                     |
| **Version Control**   | Git, GitHub                                              |
| **Hosting / Testing** | GitHub Pages, Microsoft Azure (optional)                 |
| **IDE**               | Visual Studio Code                                       |
| **Design Reference**  | Wireframes created from customer feedback analysis phase |

---

## ⚙️ Setup & Local Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/MrCoss/mortgage-calculator.git
   ```
2. Navigate to the project folder:

   ```bash
   cd mortgage-calculator
   ```
3. Open the project locally:

   * Double-click `index.html`
   * Or serve it with a local server (optional):

     ```bash
     python -m http.server
     ```
4. View it in your browser at `http://localhost:8000`.

---

## Deployment

### GitHub Pages (recommended)

1. Go to **Settings → Pages**
2. Under **Build and Deployment**, set:

   * Source → `Deploy from branch`
   * Branch → `main`
   * Folder → `/ (root)`
3. Click **Save** and wait for GitHub to build.
4. Access it at:
   **[https://mrcoss.github.io/mortgage-calculator/](https://mrcoss.github.io/mortgage-calculator/)**

### Azure Static Web Apps (optional)

1. In the Azure Portal, create a **Static Web App**.
2. Link your GitHub repo and branch.
3. Set app location to `/` and output to `/`.
4. Azure automatically builds and deploys your project.

---

## Testing

Testing focused on ensuring a seamless and accurate experience:

* **Functional Tests:** Verified EMI, interest, and total repayment calculations.
* **Usability Tests:** Validated clarity, simplicity, and mobile responsiveness.
* **Performance Tests:** Confirmed fast load times and smooth slider response under varied inputs.
* **Cross-Platform Validation:** Tested on Windows, macOS, and mobile browsers.

---

## Future Enhancements

* Integrate **Excel rate data** for historical mortgage trends.
* Add **Chart.js visualization** to show payment breakdown (principal vs interest).
* Enable **Azure Function API** integration for dynamic rate fetching.
* Implement **accessibility upgrades** (keyboard navigation, ARIA labels).
* Add **PDF export** of results for customers.

---

## Project Structure

```
mortgage-calculator/
│
├── index.html          # Main application file
├── README.md           # Documentation (this file)
└── assets/             # (Optional) images, icons, CSS, JS files
```

---

## Author

**Costas Pinto**
Frontend Developer | Cloud Enthusiast | Financial Technology Projects
Email: [costaspinto312@gmail.com](mailto:costaspinto312@gmail.com)
GitHub: [MrCoss](https://github.com/MrCoss)

---

## License

This project is licensed under the **MIT License** — free to use, modify, and distribute with attribution.


