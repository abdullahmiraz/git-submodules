| Step | Description                                    | Command                                           | Example                                            |
|------|-----------------------------------------------|---------------------------------------------------|----------------------------------------------------|
| 1    | Navigate to the root directory of your parent repository | `cd /path/to/your/parent_repository`                 | `cd "J:/Web Development by Programming Hero/Milestone 8 - Simple React"` |
| 2    | Initialize the submodule using git submodule add | `git submodule add <submodule_url> <submodule_path>` | `git submodule add https://github.com/abdullahmiraz/ema-john-shopping.git "Milestone 8 - Simple React/ema-john-simple"` |
| 3    | Commit the changes after adding the submodule  | `git add .`                                          | `git add .` |
|      |                                               | `git commit -m "Added ema-john-simple submodule"`   | `git commit -m "Added ema-john-simple submodule"` |
| 4    | Push the changes to the remote repository     | `git push origin main`                              | `git push origin main` |
| 5    | Navigate to the submodule directory           | `cd "Milestone 8 - Simple React/ema-john-simple"`    | `cd "Milestone 8 - Simple React/ema-john-simple"` |
| 6    | (Optional) Make changes to the submodule files as needed |                                                |                                                    |
| 7    | (Optional) Stage the changes                  | `git add .`                                         | `git add .` |
| 8    | (Optional) Commit the changes in the submodule| `git commit -m "Made changes to ema-john-simple submodule"` | `git commit -m "Made changes to ema-john-simple submodule"` |
| 9    | (Optional) Push the changes to the submodule's repository| `git push origin main`                             | `git push origin main` |
| 10   | Go back to the parent repository's root       | `cd ../../`                                        | `cd "../../"` |
| 11   | Stage the updated submodule reference         | `git add .`                                         | `git add .` |
| 12   | Commit the updated submodule reference        | `git commit -m "Updated ema-john-simple submodule reference"` | `git commit -m "Updated ema-john-simple submodule reference"` |
| 13   | Push the changes to the parent repository's remote | `git push origin main`                             | `git push origin main` |


**Note**:  
Please note that Steps 5 to 13 are optional and intended for making changes to the submodule and updating the parent repository to reflect those changes. If you only want to initialize the submodule and don't need to make any changes immediately, you can skip those optional steps.
