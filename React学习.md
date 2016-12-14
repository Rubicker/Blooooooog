## React学习

### JSX

JSX中可以包括JS表达式,用`{}`包括

```
const user = {
  firstName: 'John',
  lastName: 'Locked'
}
const element = (
  <h1>
    Hi,{user.firstName}
  </h1>
)
```
