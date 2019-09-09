# vue ant table点击行问题：
    ### html
```
    <a-table  :customRow="customFun" >
    </a-table>
```
```
    ### ts
    customFun(record: any, index: any) {
        return {
            on: {
                click: () => {
                  
                }
            }
        }
    }
```

# vue ant table分页可选：
    ### html
```
    <a-table :pagination="data.pagination" >
    </a-table>
```
```
    ### ts
    pagination: {
        total: 0,
        pageSize: 10,
        current: 1,
        showSizeChanger: true,
        pageSizeOptions: ['10','25','50','100'],
        onShowSizeChange: (current: any, pageSize: any) => this.data.pagination.pageSize = pageSize
    }
```