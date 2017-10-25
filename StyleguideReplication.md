## CSS CODE BIT


@import 'ui-variables
@text-color
@text-color-subtle
@text-color-highlight
@text-color-selected
@text-color-info
@text-color-success
@text-color-warning
@text-color-error
@background-color-info
@background-color-success
@background-color-warning
@background-color-error
@background-color-highlight
@background-color-selected
@app-background-color
@base-background-color
@base-border-color
@pane-item-background-color
@pane-item-border-color
@input-background-color
@input-border-color
@tool-panel-background-color
@tool-panel-border-color
@inset-panel-background-color
@inset-panel-border-color
@panel-heading-background-color
@panel-heading-border-color
@overlay-background-color
@overlay-border-color
@ui-site-color-1
@ui-site-color-2
@ui-site-color-3
@ui-site-color-4
@ui-site-color-5
@disclosure-arrow-size
@component-padding
@component-icon-padding
@component-icon-size
@component-line-height
@tab-height
@font-size
@component-border-radius
@font-family



## HTML CODE BIT


```
<!doctype html>
<html lang="en">


<input class='input-text' type='text' placeholder='Text'>
<input class='input-search' type='search' placeholder='Search'>
<textarea class='input-textarea' placeholder='Text Area'></textarea>

<label class='input-label'><input class='input-radio' type='radio' name='radio'> Radio</label>
<label class='input-label'><input class='input-radio' type='radio' name='radio' checked> Radio</label>
<label class='input-label'><input class='input-checkbox' type='checkbox' checked> Checkbox</label>
<label class='input-label'><input class='input-toggle' type='checkbox' checked> Toggle</label>
<input class='input-range' type='range'>

<div class='text-smaller'>Smaller text</div>
<div>Normal text</div>
<div class='text-subtle'>Subtle text</div>
<div class='text-highlight'>Highlighted text</div>
<div class='text-info'>Info text</div>
<div class='text-success'>Success text</div>
<div class='text-warning'>Warning text</div>
<div class='text-error'>Error text</div>

<span class='inline-block'>Normal</span>
<span class='inline-block highlight'>Highlighted</span>
<span class='inline-block highlight-info'>Info</span>
<span class='inline-block highlight-success'>Success</span>
<span class='inline-block highlight-warning'>Warning</span>
<span class='inline-block highlight-error'>Error</span>

<div class='block'>
    <label>You might want to type something here.</label>
    <atom-text-editor mini>Something you typed...</atom-text-editor>
</div>
<div class='block'>
    <label class='icon icon-file-directory'>Another field with an icon</label>
    <atom-text-editor mini>Something else you typed...</atom-text-editor>
</div>
<div class='block'>
    <button class='btn'>Do it</button>
</div>

div class='block'>
    <button class='inline-block btn'>Do it</button>
    <button class='inline-block btn'>Another</button>
    <button class='inline-block btn'>OMG again</button>
</div>

<div class='block'>
    <button class='inline-block-tight btn'>Do it</button>
    <button class='inline-block-tight btn'>Another</button>
    <button class='inline-block-tight btn'>OMG again</button>
</div>

<div class='status-ignored'>Ignored</div>
<div class='status-added'>Added</div>
<div class='status-modified'>Modified</div>
<div class='status-removed'>Removed</div>
<div class='status-renamed'>Renamed</div>

<span class='inline-block status-ignored icon icon-diff-ignored'></span>
<span class='inline-block status-added icon icon-diff-added'></span>
<span class='inline-block status-modified icon icon-diff-modified'></span>
<span class='inline-block status-removed icon icon-diff-removed'></span>
<span class='inline-block status-renamed icon icon-diff-renamed'></span>


<div class='block ui-site-1'></div>
<div class='block ui-site-2'></div>
<div class='block ui-site-3'></div>
<div class='block ui-site-4'></div>
<div class='block ui-site-5'></div>

<div class='block'>
    <span class='badge'>0</span>
    <span class='badge'>8</span>
    <span class='badge'>27</span>
    <span class='badge'>450</span>
    <span class='badge'>2869</span>
</div>

<div class='block'>
    <span class='badge badge-info'>78</span>
    <span class='badge badge-success'>3</span>
    <span class='badge badge-warning'>14</span>
    <span class='badge badge-error'>1845</span>
</div>

<div class='block'>Large <span class='badge badge-large'>8</span></div>
<div class='block'>Medium <span class='badge badge-medium'>2</span></div>
<div class='block'>Small <span class='badge badge-small'>7</span></div>

<h1 class='block'>Heading <span class='badge badge-flexible'>1</span></h1>
<h2 class='block'>Heading <span class='badge badge-flexible'>2</span></h2>
<h3 class='block'>Heading <span class='badge badge-flexible'>3</span></h3>

<div class='block'>
    <span class='badge icon icon-gear'>4</span>
    <span class='badge badge-info icon icon-cloud-download'>13</span>
    <span class='badge badge-success icon icon-octoface'>5</span>
</div>

<div class='block'>
    <button class='btn'>Button</button>
</div>
<div class='block'>
    <button class='btn btn-xs'>Extra Small Button</button>
</div>
<div class='block'>
    <button class='btn btn-sm'>Small Button</button>
</div>
<div class='block'>
    <button class='btn btn-lg'>Large Button</button>
</div>

<div class='block'>
    <button class='btn btn-primary inline-block-tight'>Primary</button>
    <button class='btn btn-primary selected inline-block-tight'>Selected Primary</button>
</div>

<div class='block'>
    <button class='btn btn-info inline-block-tight'>Info</button>
    <button class='btn btn-info selected inline-block-tight'>Selected Info</button>
</div>

<div class='block'>
    <button class='btn btn-success inline-block-tight'>Success</button>
    <button class='btn btn-success selected inline-block-tight'>Selected Success</button>
</div>

<div class='block'>
    <button class='btn btn-warning inline-block-tight'>Warning</button>
    <button class='btn btn-warning selected inline-block-tight'>Selected Warning</button>
</div>

<div class='block'>
    <button class='btn btn-error inline-block-tight'>Error</button>
    <button class='btn btn-error selected inline-block-tight'>Selected Error</button>
</div>

<div class='block'>
    <button class='btn icon icon-gear inline-block-tight'>Settings</button>
    <button class='btn btn-primary icon icon-cloud-download inline-block-tight'>Install</button>
    <button class='btn btn-error icon icon-octoface inline-block-tight'>Danger</button>
</div>

<div class='block'>
    <button class='btn icon icon-gear inline-block-tight'>Settings</button>
    <button class='btn btn-primary icon icon-cloud-download inline-block-tight'>Install</button>
    <button class='btn btn-error icon icon-octoface inline-block-tight'>Danger</button>
</div>

<div class='block'>
    <div>Normal size</div>
    <div class='btn-group'>
        <button class='btn'>One</button>
        <button class='btn'>Two</button>
        <button class='btn'>Three</button>
    </div>
</div>

<div class='block'>
    <div>Extra Small</div>
    <div class='btn-group btn-group-xs'>
        <button class='btn'>One</button>
        <button class='btn'>Two</button>
        <button class='btn'>Three</button>
    </div>
</div>

<div class='block'>
    <div>Small</div>
    <div class='btn-group btn-group-sm'>
        <button class='btn'>One</button>
        <button class='btn'>Two</button>
        <button class='btn'>Three</button>
    </div>
</div>

<div class='block'>
    <div>Large</div>
    <div class='btn-group btn-group-lg'>
        <button class='btn'>One</button>
        <button class='btn'>Two</button>
        <button class='btn'>Three</button>
    </div>
</div>

<div class='btn-toolbar'>
    <div class='btn-group'>
        <button class='btn'>One</button>
        <button class='btn'>Two</button>
        <button class='btn'>Three</button>
    </div>

    <div class='btn-group'>
        <button class='btn'>Four</button>
        <button class='btn'>Five</button>
    </div>

    <button class='btn'>Six</button>
    <button class='btn'>Seven</button>
</div>

<div class='block'>
    <div class='btn-group'>
        <button class='btn selected'>One</button>
        <button class='btn'>Two</button>
        <button class='btn'>Three</button>
    </div>
</div>

<div class='block'>
    <div class='btn-group'>
        <button class='btn'>One</button>
        <button class='btn selected'>Two</button>
        <button class='btn'>Three</button>
    </div>
</div>

<div class='block'>
    <div class='btn-group'>
        <button class='btn'>One</button>
        <button class='btn'>Two</button>
        <button class='btn selected'>Three</button>
    </div>
</div>

<div class='block'>
    <div class='btn-group'>
        <button class='btn selected'>One</button>
        <button class='btn selected'>Two</button>
        <button class='btn'>Three</button>
    </div>
</div>

<atom-panel>
    Some content
</atom-panel>

<atom-panel class='padded'>
    <div class="inset-panel padded">Some inset content</div>
</atom-panel>

<atom-panel class='padded'>
    <div class="inset-panel">
        <div class="panel-heading">An inset-panel heading</div>
        <div class="panel-body padded">Some Content</div>
    </div>
</atom-panel>

<ul class='list-group'>
    <li class='list-item'>Normal item</li>
    <li class='list-item selected'>This is the Selected item</li>
    <li class='list-item text-subtle'>Subtle</li>
    <li class='list-item text-info'>Info</li>
    <li class='list-item text-success'>Success</li>
    <li class='list-item text-warning'>Warning</li>
    <li class='list-item text-error'>Error</li>
</ul>

ul class='list-group'>
    <li class='list-item'>
        <span class='icon icon-file-directory'>Using a span with an icon</span>
    </li>
    <li class='list-item'>
        <i class='icon icon-file-directory'></i>
        <span>With .icon-file-directory using &lt;i&gt; tags</span>
    </li>
    <li class='list-item selected'>
        <span class='icon icon-file-directory'>Selected with .icon-file-directory</span>
    </li>
    <li class='list-item'>
        <span class='no-icon'>With .no-icon</span>
    </li>
    <li class='list-item'>
        <span class='icon icon-file-text'>With icon-file-text</span>
    </li>
    <li class='list-item'>
        <span class='icon icon-file-media'>With icon-file-media</span>
    </li>
    <li class='list-item'>
        <span class='icon icon-file-symlink-file'>With icon-file-symlink-file</span>
    </li>
    <li class='list-item'>
        <span class='icon icon-file-submodule'>With icon-file-submodule</span>
    </li>
    <li class='list-item'>
        <span class='icon icon-book'>With icon-book</span>
    </li>
</ul>

<ul class='list-tree'>
    <li class='list-nested-item'>
        <div class='list-item'>
            <span class='icon icon-file-directory'>A Directory</span>
        </div>

        <ul class='list-tree'>
            <li class='list-nested-item'>
                <div class='list-item'>
                    <span class='icon icon-file-directory'>Nested Directory</span>
                </div>

                <ul class='list-tree'>
                    <li class='list-item'>
                        <span class='icon icon-file-text'>File one</span>
                    </li>
                </ul>
            </li>

            <li class='list-nested-item collapsed'>
                <div class='list-item'>
                    <span class='icon icon-file-directory'>Collapsed Nested Directory</span>
                </div>

                <ul class='list-tree'>
                    <li class='list-item'>
                        <span class='icon icon-file-text'>File one</span>
                    </li>
                </ul>
            </li>

            <li class='list-item'>
                <span class='icon icon-file-text'>File one</span>
            </li>

            <li class='list-item selected'>
                <span class='icon icon-file-text'>File three .selected!</span>
            </li>
        </ul>
    </li>

    <li class='list-item'>
        <span class='icon icon-file-text'>.icon-file-text</span>
    </li>

    <li class='list-item'>
        <span class='icon icon-file-symlink-file'>.icon-file-symlink-file</span>
    </li>

    <ul class='list-tree has-collapsable-children'>
    <li class='list-nested-item'>
        <div class='list-item'>
            <span class='icon icon-file-directory'>A Directory</span>
        </div>

        <ul class='list-tree'>
            <li class='list-nested-item'>
                <div class='list-item'>
                    <span class='icon icon-file-directory'>Nested Directory</span>
                </div>

                <ul class='list-tree'>
                    <li class='list-item'>
                        <span class='icon icon-file-text'>File one</span>
                    </li>
                </ul>
            </li>

            <li class='list-nested-item collapsed'>
                <div class='list-item'>
                    <span class='icon icon-file-directory'>Collapsed Nested Directory</span>
                </div>

                <ul class='list-tree'>
                    <li class='list-item'>
                        <span class='icon icon-file-text'>File one</span>
                    </li>
                </ul>
            </li>

            <li class='list-item'>
                <span class='icon icon-file-text'>File one</span>
            </li>

            <li class='list-item selected'>
                <span class='icon icon-file-text'>File three .selected!</span>
            </li>
        </ul>
    </li>

    <li class='list-item'>
        <span class='icon icon-file-text'>.icon-file-text</span>
    </li>

    <li class='list-item'>
        <span class='icon icon-file-symlink-file'>.icon-file-symlink-file</span>
    </li>
</ul>

<ul class='list-tree has-collapsable-children '>
    <li class='list-nested-item'>
        <div class='list-item'>
            <span class='icon icon-file-text'>This is a collapsable section</span>
        </div>

        <ul class='list-tree has-flat-children'>
            <li class='list-item'>Something is here</li>
            <li class='list-item selected'>Something selected</li>
        </ul>
    </li>

    <li class='list-nested-item'>
        <div class='list-item'>
            <span class='icon icon-file-directory'>Another collapsable section</span>
        </div>

        <ul class='list-tree has-flat-children'>
            <li class='list-item'>Something is here</li>
            <li class='list-item'>Something else</li>
        </ul>
    </li>
</ul>

import SelectListView from 'atom-select-list'

const selectListView = new SelectListView({
  items: ['one', 'two', 'three'],
  elementForItem: (item) => {
    const li = document.createElement('li')
    li.textContent = item
    return li
  },
  didConfirmSelection: (item) => {
    console.log('confirmed', item)
  },
  didCancelSelection: () => {
    console.log('cancelled')
  }
})

<atom-panel class='modal'>
    <div class='select-list'>
        <ol class='list-group'>
            <li class='selected'>one</li>
            <li>two</li>
            <li>three</li>
        </ol>
    </div>
</atom-panel>

<atom-panel class='modal'>
    <div class='select-list'>
        <ol class='list-group'>
            <li class='selected'>
                <div class='status status-added icon icon-diff-added'></div>
                <div class='icon icon-file-text'>Some file</div>
            </li>

            <li>
                <div class='status status-modified icon icon-diff-modified'></div>
                <div class='icon icon-file-text'>Another file</div>
            </li>

            <li>
                <div class='status status-removed icon icon-diff-removed'></div>
                <div class='icon icon-file-text'>Yet another file</div>
            </li>
        </ol>
    </div>
</atom-panel>


atom-panel class='modal'>
    <div class='select-list'>
        <ol class='list-group'>
            <li class='selected'>
                <div class='pull-right'>
                    <kbd class='key-binding pull-right'>⌘⌥↓</kbd>
                </div>

                <span class='icon icon-file-text'>Some file</span>
            </li>

            <li>
                <div class='pull-right key-bindings'>
                    <kbd class='key-binding'>⌘⌥A</kbd>
                    <kbd class='key-binding'>⌘⌥O</kbd>
                </div>

                <span class='icon icon-file-text'>Another file with a long name</span>
            </li>

            <li>
                <div class='pull-right'>
                    <kbd class='key-binding'>⌘⌥↓</kbd>
                </div>

                <span class='icon icon-file-text'>Yet another file</span>
            </li>
        </ol>
    </div>
</atom-panel>

<atom-panel class='modal'>
    <div class='select-list'>
        <ol class='list-group'>
            <li class='two-lines'>
                <div class='primary-line'>Primary line</div>
                <div class='secondary-line'>Secondary line</div>
            </li>

            <li class='two-lines selected'>
                <div class='primary-line'>A thing</div>
                <div class='secondary-line'>Description of the thing</div>
            </li>
        </ol>
    </div>
</atom-panel>

<atom-panel class='modal'>
    <div class='select-list'>
        <ol class='list-group'>
            <li class='two-lines'>
                <div class='status status-added icon icon-diff-added'></div>
                <div class='primary-line icon icon-file-text'>Primary line</div>
                <div class='secondary-line no-icon'>Secondary line</div>
            </li>

            <li class='two-lines selected'>
                <div class='status status-modified icon icon-diff-modified'></div>
                <div class='primary-line icon icon-file-symlink-file'>A thing</div>
                <div class='secondary-line no-icon'>Description of the thing</div>
            </li>

            <li class='two-lines'>
                <div class='status status-renamed icon icon-diff-renamed'></div>
                <div class='primary-line icon icon-file-symlink-file'>A thing</div>
                <div class='secondary-line no-icon'>Description of the thing</div>
            </li>
        </ol>
    </div>
</atom-panel>

<atom-panel class='modal'>
    <div class='select-list'>
        <ol class='list-group mark-active'>
            <li class='selected'>Selected &mdash; user is arrowing through the list.</li>
            <li class='active'>This is the active item</li>
            <li class='selected active'>Selected AND Active!</li>
        </ol>
    </div>
</atom-panel>

<atom-panel class='modal'>
    <div class='select-list'>
        <atom-text-editor mini>I searched for this</atom-text-editor>
        <div class='error-message'>Nothing has been found!</div>
    </div>
</atom-panel>

<atom-panel class='modal'>
    <div class='select-list'>
        <atom-text-editor mini>I searched for this</atom-text-editor>
        <div class='error-message'>Nothing has been found!</div>
    </div>
</atom-panel>

<atom-panel class='modal'>
    <div class='select-list'>
        <atom-text-editor mini>User input</atom-text-editor>
        <div class='loading'>
            <span class='loading-message'>Chill, bro. Things are loading.</span>
            <span class='badge'>1234</span>
        </div>
    </div>
</atom-panel>

<div class='select-list popover-list'>
    <atom-text-editor mini>'User types here..'</atom-text-editor>
    <ol class='list-group'>
        <li class='selected'>one</li>
        <li>two</li>
        <li>three</li>
    </ol>
</div>

<atom-panel class='modal'>
    <div>Some content</div>
</atom-panel>
<div class='tooltip top'>
    <div class='tooltip-arrow'></div>
    <div class='tooltip-inner'>This is a message</div>
</div>

<div class='tooltip top'>
    <div class='tooltip-arrow'></div>
    <div class='tooltip-inner'>
        With a keystroke <span class="keystroke">cmd-shift-o</span>
    </div>
</div>

<ul class='error-messages block'>
    <li>This is an error!</li>
    <li>And another</li>
</ul>

<ul class='info-messages block'>
    <li>Info line</li>
    <li>Another info line</li>
</ul>

<ul class='background-message'>
    <li>No Results</li>
</ul>

<div class='block'>
    <progress class='inline-block'></progress>
    <span class='inline-block'>Indeterminate</span>
</div>

<div class='block'>
    <progress class='inline-block' max='100' value='25'></progress>
    <span class='inline-block'>At 25%</span>
</div>

<div class='block'>
    <progress class='inline-block' max='100' value='50'></progress>
    <span class='inline-block'>At 50%</span>
</div>

<div class='block'>
    <progress class='inline-block' max='100' value='75'></progress>
    <span class='inline-block'>At 75%</span>
</div>

<div class='block'>
    <progress class='inline-block' max='100' value='100'></progress>
    <span class='inline-block'>At 100%</span>
</div>

<span class='loading loading-spinner-tiny inline-block'></span>
<span class='loading loading-spinner-small inline-block'></span>
<span class='loading loading-spinner-medium inline-block'></span>
<span class='loading loading-spinner-large inline-block'></span>


</html>
```
