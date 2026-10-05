# pricing-comparison-table
Building a single-page pricing comparison using a real, accessible HTML table.


# Key aspects of this project
- **A semantic page**: Use <header>, <main>, and <footer> to structure the page itself.
- **A real** <table> with <thead> and <tbody> separating header rows from data rows.
- **A** <caption> as the first child of the table that names what is being compared.
- **Header scopes**: Use scope="col" on column headers, and scope="row" on the plan-name cells so screen readers can announce data in context.
- **At least one merged cell**: Add colspan or rowspan somewhere meaningful - a section heading above several columns, or a highlight row that spans the table.
- **Head metadata**: Set <title>, <meta charset>, and <meta viewport>.

Full details of the project is linked here: [Pricing Comparison Table](https://roadmap.sh/projects/pricing-comparison-table)

# Screenshot of completed project
![Screenshot of Pricing Comparison Table Project](/images/Project_Screenshot.png)

Live demo is here if interested! [Project Demo](https://ronnierods.github.io/pricing-comparison-table/)