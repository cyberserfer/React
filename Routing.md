# Routing

Routing is defined by

- Path which points to a component (page)

## App Set Up

need to add

npm install react-router react-router-dom --save

## match.path vs match.url

path - The path pattern used to match. Useful for building nested <Route>s

url - The matched portion of the URL. Useful for building nested <Link>s
  
Use ***match.path*** for building nested ***Routes***

Use ***match.url*** for building nested ***Links***.

## Add style to the Link tag

inline style
```
<Link to={'/home'} activeStyle={{color: 'red'}}>
```

adding a css class
```
<Link to={'/home'} activeClassName={'namedstyle'}>
```


