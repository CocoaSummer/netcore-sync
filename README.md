## 注意事项

1. Travis CI 默认 10 分钟没有输出状态，则自动停止构建
2. 阿里云仓库 push 过快时，有限流现象，前期很快，后期很慢
3. 如果 CI 构建过程失败，建议多尝试几次
4. Github Actions 限制 2000 分钟/月，请注意构建次数
