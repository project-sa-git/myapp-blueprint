FORMAT: 1A

# API Blueprint

## myapp API

# Echo Hello [/hello{?page,limit}]

## Hello myapp取得API [GET]

+ Parameters
    + page: 2  (number, optional) - ページ数    
    + limit: 15  (number, optional) - 取得件数
        + Default: `20`

+ Response 200 (text/plain)

        Hello myapp!
