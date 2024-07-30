# table-numbering
A simple obsidian plugin to automatically insert and update numbered rows in tables.
## How it works
1. you select a row in a table
2. you use the "insert numbered row below" from the command palette
3. a new row will made below the selected row and if that row had any number formated as 1. 2. 3. etc. then they and next rows will get updated accordingly.

#### Example
1. Suppose you have a table confiugured like this

<br>

![Image_1](https://github.com/masterelf425900/table-numbering/blob/main/Images/Image-1.png)

<br>

2. You select a row like this.

<br>

![Image_2](https://github.com/masterelf425900/table-numbering/blob/main/Images/Image-2.png)

<br>

3. Now Go to command palette of obsidian using shortcut Cntrl+P and select "Insert Numbered Row Below" option.

<br>

![Image_3](https://github.com/masterelf425900/table-numbering/blob/main/Images/Image-3.png)

<br>

4. Now a new row will be created below the one you had selected earlier. Which will be a copy of the selected row with the numbers added in increments of 1 (can be customized in settings for more)

<br>

![Image_4](https://github.com/masterelf425900/table-numbering/blob/main/Images/Image-4.png)

<br>

5. Now we can simply change the texts wihtout worrying about the numbers being off.

<br>

![Image_5](https://github.com/masterelf425900/table-numbering/blob/main/Images/Image-5.png)

<br>


no doubt its a niche scenario. I needed it for my games, movies and tv-shows tracking. Maybe some people will find it helpful.

## how to install
1. download the main.js and manifest.json files
2. put them in a folder with any name. I named mine "table-numbering" for easy navigation.
3. put that folder in your vaults plugin folder. Mine looks like this A:\Projects\Obsidian\Reflections\.obsidian\plugins\table-numbering

#### Bonus
If you want your tables to have the same looks as I have in the images, then simply download the Table.css file and put it in your snippet folder. The dashes can be 1 or 2px larger or smaller depending on the table size and frankly speaking, the code is quite a mess. So use it if its something you're willing to overlook just to have a clean looking table.
