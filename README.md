So, we've created a package.json file, but it's missing a few things  
that people usually expect.  If you type `npm install`, you'll see  
something like this:  

         npm WARN package.json %ID% No description  
         npm WARN package.json %ID% No repository field.  
         npm WARN package.json %ID% No README data  

Before we can share this work of art with the world, we need to make  
it a bit more polished so that people know how to use it.  

First, create a README.md file, with a few words in it.  

Then, add a "repository" field in your package.json file, with a url  
where people can access the code.  

You can edit your package.json file by hand, or run `npm init` again.  

Run `how-to-npm verify` when you're done.
