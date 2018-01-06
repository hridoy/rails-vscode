# Rails Snippets
**Now updated for latest rails version**

This extension for Visual Studio Code adds snippets for Ruby on rails. More
Snippets will be becoming soon.
## Upcoming:
- Handle Bar Template
- HAML Template
- Custom Error Solution
- Angular Rails
- Reactjs Rails
- Ember Rails
- Jasmin Rails
- Mocha Rails
- Chai Rails

![Use Extension](https://github.com/hridoy/media/raw/master/rails-preview.gif)

See the [CHANGELOG](https://github.com/hridoy/rails-vscode/master/CHANGELOG.md)
for the latest changes

# Usage
Type the helper name and replace **"_"** with **"-"**

For Example: 
  - has-many
  - def-create
  - def-show
# Controller

 For example:

| Type          | Output              |
| ------------- | ------------------- |
| `crud`        | full crud helpers   |
| `def-create`  | def create resource |
| `find-id`     | find(id)            |
| `find-params` | find(params[:id])   |

# Model

## after
    *  after-create
    *  after-save
    *  after-update
    *  after-destroy
    *  after-validation
    *  after-validation-on-create
    *  after-validation-on-Update

## before
    *  before-action
    *  before-create
    *  before-save
    *  before-validation
    *  before-destroy
    *  before-update
    *  before-validation-on-create
    *  before-validation-on-update

## has
    *  has-many
    *  has-many-through
    *  has-many-dependent
    *  has-one
    *  has-one-through
    *  has-and-belongs-to-many

## before
    *  validate
    *  validates
    *  validates-acceptance-of
    *  validates-acceptance-of-if
    *  validates-associated
    *  validates-associated-if
    *  validates-confirmation-of
    *  validates-confirmation-of-if
    *  validates-exclusion-of
    *  validates-exclusion-of-if
    *  validates-format-of
    *  validates-format-of-if
    *  validates-inclusion-of
    *  validates-inclusion-of-if
    *  validates-length-of
    *  validates-length-of-if
    *  validates-length-of-is
    *  validates-length-of-minimum
    *  validated-numericality-if
    *  validated-numericality-of
    *  validated-presence-of
    *  validated-presence-of-if
    *  validated-uniqueness-of
    *  validated-uniqueness-of-if
## Migration



| Type             | Output        |
| ---------------- | ------------- |
| `t.binary`       | Binary        |
| `t.boolean`      | Boolean       |
| `t.time`         | Time          |
| `t.timestamp`    | Timestamp     |
| `t.timestamps`   | Timestamps    |
| `t.date`         | Date          |
| `t.datetime`     | Datetime      |
| `t.decimal`      | Decimal       |
| `t.float`        | Float         |
| `t.integer`      | Integer       |
| `t.integer-lock` | Integer Lock  |
| `t.references`   | References    |
| `t.rename`       | String        |
| `t.text`         | Text          |
| `t.rename`       | Rename        |
| `t.column`       | Column        |
| `t.columns`      | Columns       |
| `add-column`     | Add Column    |
| `remove-column`  | Remove column |
| `change-column`  | Change column |
| `rename-column`  | Change column |
| `add-index`      | Add index     |
| `remove-index`   | Remove Index  |
| `create-table`   | Create Table  |
| `drop-table`     | Drop Table    |

# ERB Template
*  for-loop 
*  each
*  if
*  if-else 
*  if-unless-inline 
*  else
*  else-if 
*  end  
*  emded (%< %>)
*  emded-print (<%= %>)
*  collection-select 
*  stylesheet-link-tag 
*  submit-tag 
*  flash 
*  fixture 
*  form_tag 
*  format    
*  image_submit_tag
*  map
*  $label 
*  bye-bug    
*  buy-bug-erb


## render
    *  render
    *  render-action
    *  render-action-layout
    *  render-file
    *  render-file-path
    *  render-inline
    *  render-inline-local
    *  render-inline-type
    *  render-layout
    *  render-layout-default
    *  render-nothing
    *  render-nothing-status
    *  render-partial
    *  render-partial-collection
    *  render-partial-object
    *  render-partial-status
    *  render-text
    *  render-text-layout
    *  render-text-layout-true
    *  render-text-status
    *  render-update

# Gem
* gem-development
* gem-test
* gem-production
* gem-development-test

# Attributes
* presense
* length
* method
* delete
* data
* only
* edit
* update
* show
* destroy
* format

# Use the Snippets

Start typing the name of the helper you want (ex: "emb" for "embed") and hit Tab to insert the snippet.

Alternatively, press `Ctrl`+`Space` (Windows, Linux) or `Cmd`+`Space` (OSX) to
activate snippets from within the editor.

## Installation

1. Install Visual Studio Code 1.10.0 or higher
2. Launch Code
3. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or
   `Cmd`-`Shift`-`P` (OSX)
4. Select `Install Extension`
5. Choose the extension
6. Reload Visual Studio Code
