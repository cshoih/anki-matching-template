# Anki Matching Template

Interactive Anki template for matching questions with dropdown selections.

## Features
- ✅ Text-based matching (left labels → right dropdowns)
- ✅ Automatic shuffling of dropdown options
- ✅ Visual feedback (green ✓ / red ✗)
- ✅ Score tracking
- ✅ Keyboard shortcuts (Enter = Check, Shift+Enter = Show Answers)
- ✅ Cross-platform compatible (works on all devices)

## Installation

### 1. Create Note Type in Anki
1. Go to **Tools → Manage Note Types → Add**
2. Clone "Basic" and name it "Matching"
3. Click **Fields** and add these fields:
   - `Prompt`
   - `Image` (optional)
   - `Labels`
   - `Options`
   - `Answer1`
   - `Answer2`
   - `Answer3`
   - `Answer4`
   - `Answer5`
   - `Answer6`
   - `Answer7`
   - `Answer8`
   - `Answer9`
   - `Answer10`

### 2. Set Up Template
1. Click **Cards**
2. Copy the content from `template-front.html` and paste into **Front Template**
3. Copy the content from `template-back.html` and paste into **Back Template**
4. Click **Save**

## Usage

### Creating a Card

**Example: CNS Treatment Matching**

| Field | Content |
|-------|---------|
| **Prompt** | `Match each CNS problem to its potential treatment:` |
| **Labels** | `CSPGs\|Myelin inhibitors (Nogo-A, MAG, OMgp)\|Low growth signals\|Dead cells` |
| **Options** | `Chondroitinase ABC\|Anti-Nogo antibodies + ROCK inhibitors\|Neurotrophic factor delivery\|Cell transplantation` |
| **Answer1** | `Chondroitinase ABC` |
| **Answer2** | `Anti-Nogo antibodies + ROCK inhibitors` |
| **Answer3** | `Neurotrophic factor delivery` |
| **Answer4** | `Cell transplantation` |

**Important:** Separate items in Labels and Options with `|` (pipe character)
