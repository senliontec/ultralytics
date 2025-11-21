
#第一次设置

# 1. 克隆你的 fork
git clone https://github.com/你的用户名/ultralytics.git
cd ultralytics

# 2. 创建注释分支
git checkout -b annotations

# 3. 开始添加注释（用你喜欢的编辑器）
# 比如编辑 model.py 文件，添加中文注释

# 4. 提交更改
git add .
git commit -m "首次添加模型部分注释"

# 5. 推送到 GitHub
git push -u origin annotations




# 日常修改流程

# 1. 确保在 annotations 分支
git checkout annotations

# 2. 拉取最新更改（如果多人协作）
git pull origin annotations

# 3. 进行你的注释修改
# 编辑文件...

# 4. 提交更改
git add .
git commit -m "更新训练器部分注释"

# 5. 推送到 GitHub
git push origin annotations
