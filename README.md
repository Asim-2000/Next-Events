# Next Events

### Project Routes

1. / => Starting Page (Show Featured Events)
2. /events => Events Page (Show All Events)
3. /events/[some-id] => Event Detail Page (Show Selected Event)
4. /events/...slug => Filtered Events Page (Show Filtered Events)

Note: Files and Folders stored outside of public/ are not made accessible by NextJS - Visitors cannot load files from there. 

#### CODE ANALYSIS:
```javascript
 const humanReadableDate = new Date(date).toLocaleDateString('en-US', {
        day: "numeric",
        month: 'long',
        year:"numeric"
    })
```
