## Manual Trigger

```sh
gh workflow run manual-workflow-dispatch.yml -f name=mona -f greeting=hello -F data=@myfile.txt

echo '{"name":"mona", "greeting":"hello"}' | gh workflow run manual-workflow-dispatch.yml --json
```