Created using Bootstrap5 alpha-1 as a sample to check out bootstrap5 alpha release

The project makes use of the SASS compiler and has been installed as a dev dependency

Remove the 
<code>
 "devDependencies": {
    "sass": "^1.26.9"
  }
</code>  
from the package.json file if sass has been installed globally on your system.
If not it will install sass compiler locally and will have to be run using npx 

# Install project: 
run command
npm install

# Compile SASS files:
Make sure npx is installed globally on your system then run command

npx sass --watch scss:css

If SASS is installed globally then run command

sass --watch scss:css