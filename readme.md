<%= name %>

<%= description %>

# installation

```
npm i <%= name %>
```

# Usage

```riot
<app>
  <my-component/>

  <script>
    import MyComponent from '<%= name %>'

    export default {
      components: {
        MyComponent
      }
    }
  </script>
</app>

```