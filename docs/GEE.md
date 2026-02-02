# 授权

```bash
earthengine authenticate
earthengine set_project gee-kongdd
```

# 查询任务进度

```bash
# CANCELLED,CANCELLING,COMPLETED,FAILED,PENDING,READY,RUNNING,SUCCEEDED,UNKNOWN
earthengine task list --status RUNNING PENDING --long_format
```
