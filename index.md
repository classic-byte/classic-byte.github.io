---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Graph Representation Learning

* Q1: What is **Knowledge Graph**?

Knowledge Graph (KG) [24] is defined as a directed graph G = (V, E), where
V is the set of nodes and E ⊆ V × V is the set of edges between nodes in V. G is associated with a node type mapping function ϕ: V → A and an edge type mapping function ψ: E → R, where |A| > 1 and/or |R| > 1. Each node v ∈ V belongs to one particular node type in the node type set A: ϕ(v) ∈ A, and each edge e ∈ E belongs to a particular relation type in relation type set R: ψ(e) ∈ R. Mining knowledge graphs is usually based on a basic entity-relation-entity triplet (u,e,v), where u ∈ V, e ∈ E, v ∈ V denote the head, relation and tail of this triplet. In this paper, we refer these entity-relation-entity triplets as knowledge triplets for simplicity. Here the types of nodes u and v could be either same or different depending on the context.

From: **Deep Learning on Knowledge Graph for Recommender System: A Survey**

* Q2: What is **Graph Embedding**?
* Q3: How to get feature matrix and input to NN?
* Q4: Can we predict the attributes/features of nodes instead of the node label?

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

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
<dd>Leo</dd>
<dt>Born</dt>
<dd>1999</dd>
<dt>Birthplace</dt>
<dd>China</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
