Proposed Options for CLI interface:

  --file='path to single file to compile into selected output' | Optional
  --directory='path to directory of  multiple files to compile to selected output' | Default '.'
  --engine=['ts', 'js', '.netmodels', '.netclasses', 'xml', 'mysql', 'pg', 'mongoose', 'sequelize', 'java'] | Default 'ts'
  --ouput='path to the directory the output should be generated inside of' | Default './QuickInterfaces'
  
Examples:

  # This will generate the project-schema.json file into the ./ts/models output directory a set of TS interfaces
  node index.js --file=~/Documents/project-schema.json --engine=ts --output=./ts/models
  
  # This will iterate a list of files in a directory and create multiple files for the results into the ./QuickInterfaces dir
  node index.js --directory=~/Documents/ProjectIdeas/models --engine=js
