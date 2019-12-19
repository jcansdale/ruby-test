## Quick Start

1. Browse to https://online.visualstudio.com and authenticate

2. Create a new environment with `jcansdale/ruby-test` as the `Git Repository`

![image](https://user-images.githubusercontent.com/11719160/71179635-7bf7c500-2268-11ea-987c-d84474137186.png)

3. Load the new environment and open `targets.rb`

![image](https://user-images.githubusercontent.com/11719160/71179866-e9a3f100-2268-11ea-83cf-2436a3d32c57.png)

4. Right-click inside any Ruby method and `Debug Method`

![image](https://user-images.githubusercontent.com/11719160/71180059-51f2d280-2269-11ea-8025-898e91338dae.png)

There's a possible issue that might happen the first time the environment loads. You'll notice a `Couldn't find symbols` warning when you attempt to debug a method and no symbol names appear under `targets.rb`. If this happens, simply hit refresh on your browser and it _should_ sort itself out.

![image](https://user-images.githubusercontent.com/11719160/71179935-0fc99100-2269-11ea-990d-5f62fe8822d0.png)

https://twitter.com/jcansdale

## About

When this repository is loaded by VS Online, it will install the Ruby and TestDriven extensions using a [devcontainer](devcontainer/devcontainer.json).

- Ruby for VS Code by Peng Lv
https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby

- TestDriven for VS Code by Jamie Cansdale
https://marketplace.visualstudio.com/items?itemName=JamieCansdale.testdriven

## Misc

Have fun and let me know how you get on. Feel free to send PRs my way! 😄
