# Working with Obsidian & Quartz
## getting started
Run the following commands, but after the last command wait before you enter an instruction
```shell
git clone https://github.com/IUBSAT/home.git
cd home
npm i
npx quartz sync
```

After the last command, open up [Obsidian](https://obsidian.md) and create a new vault - select open a vault of an existing folder and select <some-dir>/home/content/ (content is the vault directory for notes pushed to github and also the website)

## syncing using quartz
To sync using quartz, just run the following command
```shell
npx quartz sync
```
>Use ```shell npx quartz sync --help``` for details on sync's usage.

Quartz's sync should be configured to push and pull by default, but make sure to always sync before/after editing the vault to prevent conflicts from arising.
