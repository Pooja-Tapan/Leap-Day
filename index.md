---
layout: default
---

# Introduction

MediaValet is providing IT pros, DAM consultants, admins and power users with a set of PowerShell Cmdlets that can be used to do heavy lifting tasks in the MediaValet DAM through the command line.

# System Requirements

> You have two options: Use Windows Powershell 5.1 or use Powershell Core.

## > Windows Powershell 5.1

If you are using Windows 10 or Windows Server 2016, you do not need to upgrade PowerShell since these operating systems ship with Windows PowerShell. Older versions of windows need to be upgraded to Windows PowerShell 5.1. The instructions on how to upgrade can be found here.

You can verify that you have the correct version of PowerShell by running PowerShell and entering the command 
```js
$PSVersionTable.PSVersion
```

This should provide you with a result showing that the Major version is 5 and the Minor version is 1.

Your machine needs to have .NET 4.7.2 before you install the MediaValet DAM PowerShell modules. In order to verify that you have .NET 4.7.2, run the following command and ensure that your release number is 461808 or higher. If you have a release number less than 461808, please install the latest .NET Framework runtime from here.

```js
Get-ChildItem "HKLM:SOFTWARE\Microsoft\NET Framework Setup\NDP\v4\Full\" | Get-ItemPropertyValue -Name Release
```
## > Powershell Core

If you work on a Mac or if you have a multi-platform environment where you work on both OsX and Windows, you should use Powershell 6.1. You can find installation instructions here.

On Windows, please check your installation by searching for the pwsh app and opening it. Then on the command prompt, enter $PSVersionTable.PSVersion. The Major version should be 6.1

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
