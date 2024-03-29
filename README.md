# KV-JSAccordions
A simple accordion functionality built on JavaScript with a dependency on jQUery.
This is still work in progress. If you feel it's missing any features or needs corrections please feel free to get in touch with me :)

## Example
https://raw.githubusercontent.com/kvaganyan/KV-JSAccordions/example/index.htm

## Usage
### Basic setup
~~~html
<h4><span class="accordion-item" data-panel-id="basic-panel1">Accordion 1</span></h4>
<div class="accordion-panel" id="basic-panel1">
    <h4>This is the content of Accordion 1</h4>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas at elit felis. Donec ac sapien a tortor efficitur consequat.</p>
</div>
<h4><span class="accordion-item" data-panel-id="basic-panel2">Accordion 2</span></h4>
<div class="accordion-panel" id="basic-panel2">
    <h4>This is the content of Accordion 2</h4>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas at elit felis. Donec ac sapien a tortor efficitur consequat.</p>
</div>
<h4><span class="accordion-item" data-panel-id="basic-panel3">Accordion 3</span></h4>
<div class="accordion-panel" id="basic-panel3">
    <h4>This is the content of Accordion 3</h4>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas at elit felis. Donec ac sapien a tortor efficitur consequat.</p>
</div>
~~~

### Open on load
~~~html
<h4><span class="accordion-item" data-panel-id="active-panel1">Accordion 1</span></h4>
<div class="accordion-panel" id="active-panel1">
    <h4>This is the content of Accordion 1</h4>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas at elit felis. Donec ac sapien a tortor efficitur consequat.</p>
</div>
<h4><span class="accordion-item active" data-panel-id="active-panel2">Accordion 2</span></h4>
<div class="accordion-panel" id="active-panel2">
    <h4>This is the content of Accordion 2</h4>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas at elit felis. Donec ac sapien a tortor efficitur consequat.</p>
</div>
~~~

### Opening non sibling objects
~~~html
<h4><span class="accordion-item" data-panel-id="distant-panel2">Accordion 1</span></h4>
<div class="accordion-panel" id="distant-panel1">
    <h4>This is the content of Accordion 1</h4>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas at elit felis. Donec ac sapien a tortor efficitur consequat.</p>
</div>
<h4><span class="accordion-item" data-panel-id="distant-panel1">Accordion 2</span></h4>
<div class="accordion-panel" id="distant-panel2">
    <h4>This is the content of Accordion 2</h4>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas at elit felis. Donec ac sapien a tortor efficitur consequat.</p>
</div>
~~~

### Nesting accordions
~~~html
<h4><span class="accordion-item" data-panel-id="nesting-panel1">Accordion 1</span></h4>
<div class="accordion-panel" id="nesting-panel1">
    <h4>This is the content of Accordion 1</h4>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas at elit felis. Donec ac sapien a tortor efficitur consequat.</p>
    <h4><span class="accordion-item" data-panel-id="nesting-panel11">Accordion 1.1</span></h4>
    <div class="accordion-panel" id="nesting-panel11">
        <h4>This is the content of Accordion 1.1</h4>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas at elit felis. Donec ac sapien a tortor efficitur consequat.</p>
    </div>
</div>
<h4><span class="accordion-item" data-panel-id="nesting-panel2">Accordion 2</span></h4>
<div class="accordion-panel" id="nesting-panel2">
    <h4>This is the content of Accordion 3</h4>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas at elit felis. Donec ac sapien a tortor efficitur consequat.</p>
    <h4><span class="accordion-item" data-panel-id="nesting-panel21">Accordion 2.1</span></h4>
    <div class="accordion-panel" id="nesting-panel21">
        <h4>This is the content of Accordion 2.1</h4>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas at elit felis. Donec ac sapien a tortor efficitur consequat.</p>
    </div>
    <h4><span class="accordion-item" data-panel-id="nesting-panel22">Accordion 2.2</span></h4>
    <div class="accordion-panel" id="nesting-panel22">
        <h4>This is the content of Accordion 2.2</h4>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas at elit felis. Donec ac sapien a tortor efficitur consequat.</p>
    </div>
    <h4><span class="accordion-item active" data-panel-id="nesting-panel23">Accordion 2.3</span></h4>
    <div class="accordion-panel" id="nesting-panel23">
        <h4>This is the content of Accordion 2.3</h4>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas at elit felis. Donec ac sapien a tortor efficitur consequat.</p>
    </div>
</div>
~~~

## License
KV-JSAccordions is released under the MIT license.
