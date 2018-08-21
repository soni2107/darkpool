

### Folder Structure
1. **config** - basic configurations like show normal user ui or admin ui and other flags, basically if you want to make any big changes just make changes to config file ex choosing one trading algorith from two. etl, java and c# can parse this file, get parameters for their functions and run their program

2. **docs** - basic documentation

3.  **src** - main code file 

3.1 **tests** - unitests and test cases, to ensure code doesn't break

3.2  **main**  - everything goes here

3.2.1 **database** - for all data and sql
3.2.2 **java** - it has **3** sub-folders, 1.**tools** - for all the helper files and helper functions , 2.**build** - it will have main.java and the one file that'll run and import things from tools. 3. **lib** - libraries

3.2.3 **ui** - it has **3** subfolders 1. **static** for all the static content like images, etc 2.**lib** - libraries 3. **dark_wpf** - wpf app with bin, obj and properties subfolders