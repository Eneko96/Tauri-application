# Modern Desktop App Template

A repository containing boilerplate for your application. This is nota project to clone. Neither is it an alternative tutorial to my video tutorials. I didn't use svelte because its performance comes at the cost of UI kits; In the future, either React improves or material svelte UI kit catches up with material react UI kit.

## Instructions

1. Follow only the Tauri [prerequisites](https://tauri.studio/docs/getting-started/prerequisites)
2. Create the frontend project with `yarn create vite APP-NAME --template react[-ts]` and press enter for the package name
3. Run `yarn add -D @tauri-apps/cli`
4. Now copy the contents of each file in this repo excluding `README.md` into the corresponding file of your project. For example my `package.json`. 
5. Run `yarn` to install dependencies
6. Run `yarn dev` to start developing
7. If any problems arise, open an issue

## Tips

Set `alwaysOnTop` to `true` in `tauri.conf.json` to avoid alt tabbing.

## Screenshots

![image](https://user-images.githubusercontent.com/21298211/160052266-9f9ea8ec-6964-4f76-bccb-2913998e5b23.png)

![image](https://user-images.githubusercontent.com/21298211/160052283-5ee37ed7-be8e-4713-bdb3-2d4279afc36f.png)
