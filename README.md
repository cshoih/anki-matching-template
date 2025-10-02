# Anki Matching Template

Interactive Anki template for matching questions with dropdown selections.

<div align="center">
  <table>
    <tr>
      <td width="50%">
        <img width="100%" alt="clinical scenario demo" src="https://github.com/user-attachments/assets/e6fc4eb3-054b-4e08-b115-9581f55e60e1" />
        <p align="center"><i>Clinical Scenario Matching</i></p>
      </td>
      <td width="50%">
        <img width="100%" alt="Screenshot 2025-10-03 at 2 29 53 am" src="https://github.com/user-attachments/assets/cd12bbbe-fa91-409b-bd23-8a69102becaa" />
        <p align="center"><i>Anatomy</i></p>
      </td>
    </tr>
  </table>
</div>





## Features
- ✅ Text-based matching (left labels → right dropdowns)
- ✅ Automatic shuffling of dropdown options
- ✅ Visual feedback (green ✓ / red ✗)
- ✅ Score tracking
- ✅ Keyboard shortcuts (Enter = Check, Shift+Enter = Show Answers)
- ✅ Cross-platform compatible (works on all devices)


## Installation

### Option 1: Download Ready-to-Use Deck
1. **Download:** [`anki-matching-template.apkg`](anki-matching-template.apkg)
2. **Import:** Double-click the file or go to **File → Import** in Anki
3. **Done!** The note type and sample cards are ready to use

---
### Option 2: Manual Setup
Follow the installation instructions below to set up the template manually.
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

<div align="center">
  <table>
    <tr>
      <td width="33%">
        <img width="100%" alt="card-making demo image 1" src="https://github.com/user-attachments/assets/5e07e065-cbda-42fa-97d3-a2e4b383efc9" />
        <p align="center"><i>Card Creation Process 1</i></p>
      </td>
      <td width="33%">
        <img width="100%" alt="card-making demo image 2" src="https://github.com/user-attachments/assets/4f2f78e2-bff1-4403-84f5-d8e2ed229daf" />
        <p align="center"><i>Card Creation Process 2</i></p>
      </td>
      <td width="34%">
        <img width="100%" alt="card-outcome-demo-image-3" src="https://github.com/user-attachments/assets/8d61038f-ea8e-455b-91ba-7302835e3d02" />
        <p align="center"><i>Final Matching Interface</i></p>
      </td>
    </tr>
  </table>
</div>


