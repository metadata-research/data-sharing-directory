## Contributing to the directory

### [Adding a Standard, Tool or Community Initiative](https://metadata-research.github.io/data-sharing-directory/)

To add a new entry to one of the following categories: Standards, Tools, or Community Initiatives (or to edit an existing entry), begin by forking the repository to create your own copy of the directory, adding (or editing) the entry, committing your additions/changes, and submitting a pull request to the original repository.

1. Sign into your GitHub account.
   If you don't have one, here's how to [set one up](https://github.com/join)

2. Fork the repository using the button at the upper right. The fork button looks like this:
   
   You have just created a copy of the directory for your personal use. The changes you make here will not be final
   until you have submitted them as a pull request, and the pull    request has been merged into the origin repository
   by a repo maintainer. More on pull requests below. 
   After forking, the URL for your repository should look something like the following:
   github.com/[your-user-name]/data-sharing-directory/tree/gh-pages

   And the title of the directory at the top of your page should be: 
   [your-user-name]/data-sharing-directory

   3. In your forked directory, navigate to the ‘initiatives’, 'standards', or ‘tools’ directory and open
      the sub-folder named ‘data’. You will see a list of files, one for each entry. 

      To add a new item, click ‘Add file’ (in the upper right-hand area, as shown above in Figure 2), and select ‘add new file’. 
   
      Give your file a descriptive name, using lowercase letters and hyphens instead of spaces, and give it a .yml file extension. (Ex: creative-commons.yml).

      YAML is a data serialization language. If you are unfamiliar with YAML syntax, refer to the files in the _templates directory [official YAML sample file](http://www.yaml.org/start.html)

      YAML is a data serialization language. If you are unfamiliar with YAML syntax, refer to the files in the _templates directory official YAML sample file.
   
      Use the following format to create the code for your new entry
   
```
code

```

      NOTE – Important! If your text contains any colons, delete, escape, or replace them with another character. Colons in text results in an error in the code and the new file will not be added.

      There are templates for each type in the folder named _templates in the main directory. 

 4. To make changes to an entry, open the file and click the pencil in the upper right-hand area to edit, following formatting 
    instructions as above. It is helpful to turn on ‘Soft wrap’, which appears on the right as soon as you open a file for editing. This allows you to see all the text without scrolling to the right.
   
   More than one sub-category or type can be included for any entry, i.e. a resource may be both a standard and a tool. If you include more than one, enter each on a separate line, indented with a preceding ‘–‘. If there is only one, enter it on the same line after the colon. See Figure 3, where the Creative Commons example has two sub-categories and a single type.
   
   Types are standards, tools, and community initiatives.

   Sub-category options include Rights, Licensing, Metadata, Ontologies, and Informational Resources [this may be changed or expanded]
