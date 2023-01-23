# Style Sheet to be used in different visualization projects

## Classes to use for styling AntD components and different UI components

### Parent Container
_All the div should be within a parent container for consistent styling with UNDP design style_
__Require class__: `undp-container`
__Additonal Variations Classes for max-width 1280px__: `max-width`

### Typography
__h1__: Required class `undp-typography`
__h2__: Required class `undp-typography`
__h3__: Required class `undp-typography`
__h4__: Required class `undp-typography`
__h5__: Required class `undp-typography`
__h6__: Required class `undp-typography`
__p__: Required class `undp-typography`

### Text Link
__a__: Required class `undp-style`

### hr
__Required class__: `undp-style`

### For Buttons
__Required Class__: `undp-button`
__Additonal Variations Classes__: `button-primary` `button-secondary` `button-tertiary` `button-arrow` `disabled`

### Labels for Dropdowns, Checkbox, Radio Button or Text Fields
__Required Class__: `label`

### For Selection Dropdown from AntD
__Required Class For `Select` tag__: `undp-select`
__Required Class For `Option` tag__: `undp-select-option`

### For Language Selection Dropdown from AntD
__Required Class For `Select` tag__: `undp-select undp-language-select`
__Required Class For `Option` tag__: `undp-select-option`

### For Checkbox from AntD
__Required Class For `Checkbox` tag__: `undp-checkbox`

### For Radio from AntD
__Required Class For `Radio` tag__: `undp-radio`

### For Text Input from AntD
__Required Class For `Input` tag__: `undp-input`

### For Password Input from AntD
__Required Class For `Input.Password` tag__: `undp-input`

### For Number Input from AntD
__Required Class For `InputNumber` tag__: `undp-input`

### For Date Input from AntD
__Required Class For `DatePicker` tag__: `undp-input`

### For Text Area Input from AntD
__Required Class For `Input.TextArea` tag__: `undp-text-area`

### For Tabs from AntD
__Required Class For `Tabs` tag__: `undp-tabs`

### For Modal from AntD
__Required Class For `Modal` tag__: `undp-modal`

### For Slider from AntD
__Required Class For `Slider` tag__: `undp-slider`

### For Large Segmented from AntD
__Required Class For `Segmented` tag__: `undp-segmented` (this can be used to mavigate to different pages in place of tabs)

### For Small Segmented from AntD
__Required Class For `Segmented` tag__: `undp-segmented-small` (this can be used to filters or option selection)

### For Stat Cards
__Required Claas for Container div__: `stat-card-container`
__Required Class__: `stat-card`

### For Table
To build a table is slightly complicated. Instead of using `th` and `td` we use `div` for better flexibility of layouts and children divs.

Dummy table head code
```
<div className='undp-table-head undp-table-head-sticky'>
  <div style={{ width:'15%' }} className='undp-table-head-cell'>
    Head 1
  </div>
  <div style={{ width:'30%' }} className='undp-table-head-cell'>
    Head 2
  </div>
  <div style={{ width:'55%' }} className='undp-table-head-cell'>
    Head 3
  </div>
</div>
```
__Required Class for The Parent Div__: `undp-table-head` or `undp-table-head-small`
__Additonal Variations Classes__: `undp-table-head-sticky` if the head needs to stick on the top while scrolling the table
__Required Class for Individual Head Cells__: `undp-table-head-cell`

Dummy table row code
```
<div className='undp-table-row'>
  <div style={{ width:'15%' }} className='undp-table-row-cell'>
    Head 1
  </div>
  <div style={{ width:'30%' }} className='undp-table-row-cell'>
    Head 2
  </div>
  <div style={{ width:'55%' }} className='undp-table-row-cell'>
    Head 3
  </div>
</div>
```
__Required Class for The Parent Div__: `undp-table-row` or `undp-table-row-small`
__Required Class for Individual Head Cells__: `undp-table-head-cell` or `undp-table-row-cell-small`

### For Chips
__Required Class for the div__:`undp-chip`
__Additonal Variations Classes__: `undp-chip-small` `undp-chip-large` `undp-chip-red` `undp-chip-yellow` `undp-chip-blue` `undp-chip-green` `undp-chip-clickable`

### For Custom Scrollbar
__Required Class For parent element__: `undp-scrollbar`

### For Loader
__Required Class For div__: `undp-loader`

## Different CSS variable

### Color Variables

__--blue-100__: `#B5D5F5`

__--blue-200__: `#94C4F5`

__--blue-300__: `#6BABEB`

__--blue-400__: `#4F95DD`

__--blue-500__: `#3288CE`

__--blue-600__: `#006EB5`

__--blue-700__: `#1F5A95`

__--white__: `#FFF`

__--gray-100__: `#FAFAFA`

__--gray-200__: `#F7F7F7`

__--gray-300__: `#EDEFF0`

__--gray-400__: `#D4D6D8`

__--gray-500__: `#A9B1B7`

__--gray-600__: `#55606E`

__--gray-700__: `#232E3D`

__--black__: `#000`

__--light-yellow__: `#FFE17E`

__--yellow__: `#FFEB00`

__--dark-yellow__: `#FBC412`

__--light-red__: `#FFBCB7`

__--red__: `#EE402D`

__--dark-red__: `#D12800`

__--light-green__: `#B8ECB6`

__--green__: `#6DE354`

__--dark-green__: `#59BA47`

__--light-azure__: `#A2DAF3`

__--azure__: `#60D4F2`

__--dark-azure__: `#00C1FF`

### Spacing Variables

__--spacing-00__: `0`

__--spacing-01__: `0.125rem`

__--spacing-02__: `0.25rem`

__--spacing-03__: `0.5rem`

__--spacing-04__: `0.75rem`

__--spacing-05__: `1rem`

__--spacing-06__: `1.5rem`

__--spacing-07__: `2rem`

__--spacing-08__: `2.5rem`

__--spacing-09__: `3rem`

__--spacing-10__: `4rem`

__--spacing-11__: `5rem`

__--spacing-12__: `6rem`

__--spacing-13__: `7rem`

_1rem = 16px_
