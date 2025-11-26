# TaxPro 2025 - Webapp Walkthrough

I have successfully transformed your static tax guide into a modern, interactive **Tax Calculator Web Application** and completely redesigned the **Tax Guide**.

## Key Changes

### 1. New Calculator Dashboard (`index.html`)
The main page is now a fully functional calculator with a premium, clean design.
- **Income Section**: Enter Salary, Bonus, and Other Income.
- **Deductions Section**: A dynamic list where you can add various deductions.
  - **[NEW] Custom Deductions**: Select "ค่าลดหย่อนอื่นๆ (ระบุเอง)" to add any new or special deductions manually.
- **Real-time Summary**: As you type, the tax is recalculated instantly.
- **Tax Steps**: Shows exactly how the tax is calculated for each income bracket.

### 2. Modern Knowledge Base (`guide.html`)
The guide has been completely overhauled with a beautiful, modern design.
- **Hero Section**: Attractive gradient header.
- **Card-Based Layout**: Easy-to-read content blocks with icons.
- **Sticky Navigation**: Quick access to any section via the sidebar.
- **Visual Aids**: Diagrams for tax formulas and step-by-step examples.

### 3. PDF Export
- Added a **"ดาวน์โหลด PDF"** button in the summary card.
- Generates a clean PDF of your current calculation for your records.

## How to Use

1. **Open `index.html`** in your browser.
2. **Enter Income**: Type your monthly salary and yearly bonus.
3. **Add Deductions**:
   - Select a type from the dropdown.
   - If selecting "Other", type the name of the deduction (e.g., "Shop Dee Mee Kuen").
   - Enter the amount.
4. **View Result**: The "สรุปภาษี" panel on the right updates automatically.
5. **Read Guide**: Click "คู่มือภาษี" in the top bar to see the new beautiful guide.

## Technical Details
- **Framework**: Vanilla HTML/CSS/JS.
- **Styling**: Custom CSS with a modern color palette (Blue/Slate) and responsive design.
- **Libraries**: Used `html2pdf.js` (via CDN) for PDF generation and `FontAwesome` for icons.
