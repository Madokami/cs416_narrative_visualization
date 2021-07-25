## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Madokami/cs416_narrative_visualization/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Madokami/cs416_narrative_visualization/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

## Narrative visualization test
<svg width=300 height=300>

<script>
  pop_growth = [1.30072410817561,1.7243462047616,2.08332248580949,2.05319982551457,2.05524143402917,2.10866788828604,2.04952806653054,2.0557795099968,2.08817694565934,2.09125276275897,2.13311686340344,2.03121137162374,1.98294336877748,1.92954936287425,1.8558336723775,1.79507967654773,1.74961533313858,1.74802018504161,1.7620417897177,1.74866104222924,1.76406767844979,1.80049048590014,1.78432403887979,1.74712530080474,1.74895086012958,1.76830078138659,1.78300118456379,1.77018316822685,1.73856862522462,1.73544185116863,1.66842050994094,1.57292819054604,1.56456504240188,1.52044016094899,1.50599110708553,1.45269465711498,1.427219157415,1.39160819986147,1.35179096679923,1.32307577883421,1.2975934295266,1.27680831188725,1.26147763010064,1.25426340053367,1.24692384480321,1.24369497414078,1.23574121285958,1.24085406678891,1.22174269013,1.20333276891564,1.17025832977265,1.18393451235548,1.18384476275419,1.18021596062547,1.16873977624677,1.16374431044332,1.14385698082209,1.10615060940842,1.06513053318513,1.03599084817998];
d3.select("svg").selectAll("rect").data(pop_growth).enter().append("rect").attr("x", (d, i) => i).attr("width", 2).attr("height", (d) => d);
</script>
