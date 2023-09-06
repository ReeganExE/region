
> Prints IP & Agent's Region

```yml
- uses: reeganexe/region@v1
  id: ip

- name: Running on ${{ steps.ip.outputs.region }}
  run: echo "${{ steps.ip.outputs.region }}"
```
