# IFC5 Custom Schemas
This repo is created to showcase how domain specific schemas might look like. While I am a member of buildingSMART Germany, buildingSMART hasnt tasked me with doing this. I am just a curious guy trying to experiment. 
So take everything with a grain of salt. 
Feel free to add some schemas if you are motivated. 

# If you want to add a schema
1. Create a directory in `Schemas`
2. Add your schema in `.ifcx` format
3. Write a little explination using this layout in the README file
```
# Where are the parameters taken from?

# Is there anything special going on?

```
4. Add an example file in `.ifcx`, that demonstrates how its used. 

>[!Tip] 
I used the schemas I am publishing here in sample files (for the official `hello-wall.ifcx` exmaple). However the official [Viewer](https://ifc5.technical.buildingsmart.org/viewer/) doesnt seem to fetch the schemas, even if they are publically available on github and imported in the `import` section in the `.ifcx` file. Therefore the affected schema is hardcoded in the custom schema section in each sample file. 
