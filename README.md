# API Restfull with Deno, Oak and Postgresql

![Drag Racing](deno.png)

Assuming you already have deno installed, but if you haven't already:

```bash
    $ curl -fsSL https://deno.land/x/install/install.sh | sh
```
```bash
    $ cargo install deno
```

### Run

 ```bash
    $ deno run --allow-env --allow-net --allow-read main.ts
 ```

 ### Routes Api 

> Fetch data users  
 ```GET /api/v1/users```

> Fetch data user by id    
```GET /api/v1/users/:id ```

> Create data user   
```POST /api/v1/users```

> Update data user by id   
```PATCH /api/v1/users/:id```

> Delete data user by id    
```DELETE /api/v1/users/:id```