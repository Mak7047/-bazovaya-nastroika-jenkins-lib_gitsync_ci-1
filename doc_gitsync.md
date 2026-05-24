## Инициализация гитсинха (один раз)

// Основной хран
gitsync init -u DeployGit C:\1C\Demo83_UP_Storage\ C:\otus_JenkinsExample-storage_1c\src\cf\

// Хран Yaxunit
gitsync init -u DeployGit -e YAXUNIT C:\StorageOtus_yaxunit\ C:\otus_JenkinsExample-storage_1c\src\cfe\yaxunit\

## Синхронизация с хранилищем

gitsync sync -u DeployGit C:\1C\Demo83_UP_Storage\ C:\otus_JenkinsExample-storage_1c\src\cf\