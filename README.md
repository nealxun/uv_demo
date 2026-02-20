## uv operations
- `uv python list` — 列出uv支持的python版本
- `uv init` — 创建工程
- `uv python pin 3.13` - use certain python version
- `uv add --dev ipykernel` - add ipykernel to run jupyter notebook
- `uv add numpy pandas` — 添加依赖
- `uv sync` - sync with the updated pyproject.toml file

- `uv run -p 3.13 python` — 运行python交互界面
- `uv run xxx.py` — 使用系统python或当前工程的虚拟环境运行xxx.py
- `uv tree` — 打印依赖树
- `uv remove pydantic_ai` — 删除依赖
- `uv build` — 编译工程

## git operations
- To add a remote, first create a repo in GitHub. 
- Then add the remote in terminal via `git remote add origin REMOTE-URL`.
- Verify the remote was added correctly: `git remote -v`.
- Push the local repo to GitHub: `git push -u origin main`. If your local branch name is master, change the name to main via `git branch -M main` then push.
- Later on, after you commit on your local repo, use `git push --all` to push the changes to the remote.