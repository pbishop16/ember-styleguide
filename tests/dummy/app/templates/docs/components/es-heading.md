# Heading

{{#docs-demo as |demo|}}
  {{#demo.example name='es-heading'}}
    {{es-heading headingText='This is a heading text'}}
  {{/demo.example}}
  {{demo.snippet 'es-heading'}}
{{/docs-demo}}

{{#docs-demo as |demo|}}
  {{#demo.example name='es-heading-block'}}
    {{#es-heading}}
      This is a heading text <span>🐹</span>
    {{/es-heading}}
  {{/demo.example}}
  {{demo.snippet 'es-heading-block'}}
{{/docs-demo}}

{{#docs-demo as |demo|}}
  {{#demo.example name='es-heading-centered'}}
    {{es-heading headingText='This is a heading text' isCentered=true}}
  {{/demo.example}}
  {{demo.snippet 'es-heading-centered'}}
{{/docs-demo}}

{{#docs-demo as |demo|}}
  {{#demo.example name='es-heading-page-heading'}}
    {{es-heading headingText='This is a heading text' isPageHeading=true}}
  {{/demo.example}}
  {{demo.snippet 'es-heading-page-heading'}}
{{/docs-demo}}

{{#docs-demo as |demo|}}
  {{#demo.example name='es-heading-page-uppercase'}}
    {{es-heading headingText='This is a heading text' isPageHeading=true isUppercase=true}}
  {{/demo.example}}
  {{demo.snippet 'es-heading-page-uppercase'}}
{{/docs-demo}}

{{#docs-demo as |demo|}}
  {{#demo.example name='es-heading-h2'}}
    {{es-heading tagName='h2' headingText='This is a heading text h2' isPageHeading=true}}
  {{/demo.example}}
  {{demo.snippet 'es-heading-h2'}}
{{/docs-demo}}

{{#docs-demo as |demo|}}
  {{#demo.example name='es-heading-h3'}}
    {{es-heading tagName='h3' headingText='This is a heading text h3' isPageHeading=true}}
  {{/demo.example}}
  {{demo.snippet 'es-heading-h3'}}
{{/docs-demo}}

{{#docs-demo as |demo|}}
  {{#demo.example name='es-heading-h4'}}
    {{es-heading tagName='h4' headingText='This is a heading text h4' isPageHeading=true}}
  {{/demo.example}}
  {{demo.snippet 'es-heading-h4'}}
{{/docs-demo}}

{{#docs-demo as |demo|}}
  {{#demo.example name='es-heading-h5'}}
    {{es-heading tagName='h5' headingText='This is a heading text h5' isPageHeading=true}}
  {{/demo.example}}
  {{demo.snippet 'es-heading-h5'}}
{{/docs-demo}}

{{#docs-demo as |demo|}}
  {{#demo.example name='es-heading-h6'}}
    {{es-heading tagName='h6' headingText='This is a heading text h6' isPageHeading=true}}
  {{/demo.example}}
  {{demo.snippet 'es-heading-h6'}}
{{/docs-demo}}
