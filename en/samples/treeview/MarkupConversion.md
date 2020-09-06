---
title: "Markup Conversion"
date: 2020-08-25T20:22:00-04:00
---
Convert an existing list, or nested lists, into a dynamic treeview.
<!--more--> 
The treeview will convert static markup of a `ul` element into a treeview control with the addition of the `eweeye-treeview` class being added to the root element.

{{< code lang="html" >}}
<ul class="eweeye-treeview">
  ...
</ul>
{{< /code >}}

<!-- Samples Section -->
{{< html >}}
<div class="row">
{{< /html >}}

<!-- Without Treeview Section -->
{{< html >}}
<div class="col-xs-12 col-md-6">
{{< /html >}}

## Without Treeview
No Treeview Class Identified

{{< html >}}
<div class="card">
    <div class="card-body">
{{< sample/treeview >}}
    </div>
</div>
{{< /html >}}

{{< html >}}
</div>
{{< /html >}}

<!-- With Treeview Section -->
{{< html >}}
<div class="col-xs-12 col-md-6">
{{< /html >}}
## With Treeview
Treeview Class Identified
{{< html >}}
<div class="card">
    <div class="card-body">
{{< sample/treeview class="eweeye-treeview" >}}
    </div>
</div>
{{< /html >}}

{{< html >}}
</div>
{{< /html >}}

{{< html >}}
</div>
{{< /html >}}