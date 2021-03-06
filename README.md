# ccs2021 website content
The ccs2021 website content is created based on pages in this repository. 

## How to edit a page 

To edit those pages, you need a GitHub account. 

If you're a validated CCS2021 Organisation Committee member, any change you make is immediately visible on the website. If not, you need to make a _pull request_, and an authorised member must validate it to appear on the website.

To edit a page, just clic the edit button (pencil) on the top-right corner. When you're finished, push the green button at the bottom. You can optionnally describe your change. All the history of changes is available, so we can revert to older version in case of a mistake.

## There are two types of pages:

- .md files are in markdown format (https://techinch.com/blog/how-to-markdown): you can write text, with titles, bold, hyperlinks, etc.
- .json files contain _structured_ information, typically a list of person with their personal information. This structured information is automatically translated to appear on the CCS2021 website as formatted content (grid of photos...)

## Some comments on markdown files:

The CCS2021 website recognizes three levels of titles: 
- `#`: main title (large font, underlined)
- `##`: Level 2 title
- `###`: Level 3 title.

## Some comments on .json files:

If you're not familiar with .json, feel free to ask the web chair. The best to create a new entry is to copy-paste an existing one and to modify it. In summary:

-`[]` corresponds to ordered list of elements
-`{}`corresponds to dictionaries, i.e. `{"name":"remy"}` means that the name of the person is `remy`.

If you're afraid of doing mistake, you can use an online json editor such as: https://jsoneditoronline.org/#left=local.voluto&right=local.rosuwe . Paste the file content on the right, see it as a strcutured tree on the right. Edit fields or add elements with the visual interface, convert back to json, and copy paste the whole page back to the file here.
