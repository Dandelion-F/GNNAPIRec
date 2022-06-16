## GNNAPIRec

## Dataset
- SH_S
  - List.txt：200 行，对应 200 个项目（过滤掉项目的不同版本，只留下唯一版本？）
  - xxxx.txt：400 个文件，对应 400 个项目，项目 id 以文件名命名（去掉后缀，即文件名长度为 44，项目 id 长度为 40）
  - evaluation -> round(1-10)
    - APIUsagePatterns
    - GroundTruth
    - LevenshteinDistance
    - Recommendations
    - Similarities
    - TestingInvocations