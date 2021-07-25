---
title: "Css Test"
date: 2021-06-13T05:13:20+01:00
draft: false
---

Use to test styles and variations on styles.

# h1 Heading
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading


Lorem ipsum dolor sit amet, graecis denique ei vel, at duo primis mandamus. Et legere ocurreret pri, animal tacimates complectitur ad cum. Cu eum inermis inimicus efficiendi. Labore officiis his ex, soluta officiis concludaturque ei qui, vide sensibus vim ad.


**rendered as bold text**

_rendered as italicized text_

~~Strike through this text.~~

> **Fusion Drive** combines a hard drive with a flash storage (solid-state drive) and presents it as a single logical volume with the space of both drives combined.


+ Lorem ipsum dolor sit amet
+ Consectetur adipiscing elit
+ Integer molestie lorem at massa
+ Facilisis in pretium nisl aliquet
+ Nulla volutpat aliquam velit
  - Phasellus iaculis neque
  - Purus sodales ultricies
  - Vestibulum laoreet porttitor sem
  - Ac tristique libero volutpat at
+ Faucibus porta lacus fringilla vel
+ Aenean sit amet erat nunc
+ Eget porttitor lorem

1. Lorem ipsum dolor sit amet
4. Consectetur adipiscing elit
2. Integer molestie lorem at massa
8. Facilisis in pretium nisl aliquet
4. Nulla volutpat aliquam velit
99. Faucibus porta lacus fringilla vel
21. Aenean sit amet erat nunc
6. Eget porttitor lorem

In this example, `<section></section>` should be wrapped as **code**.

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code

```js
grunt.initConfig({
    assemble: {
    options: {
        assets: 'docs/assets',
        data: 'src/data/*.{json,yml}',
        helpers: 'src/custom-helpers.js',
        partials: ['src/partials/**/*.{hbs,md}']
    },
    pages: {
        options: {
        layout: 'default.hbs'
        },
        files: {
        './': ['src/templates/pages/index.hbs']
        }
    }
    }
};
```


| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |


[Assemble](http://assemble.io)

[Upstage](https://github.com/upstage/ "Visit Upstage!")

{{%expand%}}
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
{{% /expand%}}


{{<mermaid align="left">}}
graph LR;
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
{{< /mermaid >}}

{{% notice note %}}
A notice disclaimer
{{% /notice %}}

{{% notice info %}}
An information disclaimer
{{% /notice %}}


{{% notice tip %}}
A tip disclaimer
{{% /notice %}}


{{% notice warning %}}
A warning disclaimer
{{% /notice %}}

