# QuickBooks Online Card - Enhanced Design Prototype

Interactive prototype demonstrating the enhanced QuickBooks Online card for HCP's service editing interface.

🔗 **[View Live Prototype](https://YOUR-USERNAME.github.io/qbo-card-prototype/)** ← Update this URL after deployment

---

## 📋 Project Context

**Jira Ticket**: [CAF-2769](https://housecall.atlassian.net/browse/CAF-2769) - Expand supported account types for PriceBook items

**Confluence**: [Self-healing broken item links 1-Pager](https://housecall.atlassian.net/wiki/spaces/CAF/pages/2796651908/)

**Design System**: Official HCP Design System (Figma: `yDipxk8KeTUDaBsta4cez7`)

---

## ✨ Features Demonstrated

### Four Interactive States

1. **Default State** - Base configuration without QB link
2. **Linked Item State** - Shows connected QB item with inline search
3. **Search State** - Live dropdown filtering as you type
4. **Broken Link State** - Error banner with recovery options

### Key Functionality

- ✅ **Inline Search** - No modal, search appears inline
- ✅ **Live Dropdown** - Real-time filtering of QB items
- ✅ **Create & Confirm** - Flow for creating new items in QB
- ✅ **Two-Dropdown System** - Account Type + Account Sub-Type (30+ options)
- ✅ **Error Handling** - Pink error banner for deleted items
- ✅ **Official Design System** - Uses exact HCP color tokens, typography, and spacing

---

## 🎮 How to Use

1. **Open the prototype** (link above)
2. **Use state switcher buttons** to explore different scenarios
3. **Try interactive elements**:
   - Click "Edit item link" → Search appears
   - Type in search box → Dropdown filters
   - Type non-existent item → "Create and link" appears
   - Click create → Confirmation modal opens

---

## 🎨 Design System

Built using the official HCP design system with exact color tokens, typography (Inter font), and 8px border radius.

---

## 🏗️ Technical Details

- **Single HTML file** - No dependencies
- **File Size**: ~52KB
- **Browser Support**: Chrome, Safari, Firefox, Edge

---

**Created**: February 20, 2026
**Status**: Ready for Engineering Handoff ✅
