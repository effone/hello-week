# Highlight Dates

Set day/days highlight, with different customizes.

#### HTML Structure
```html
<div class="hello-week"></div>
```

#### Javascript Initialization
```js
const calendar = new HelloWeek({
    daysHighlight: [
        {
            days: ['2019-03-22'],
            backgroundColor: '#f08080',
            title: 'Dad Birthday'
        },
        {
            days: ['2019-12-18'],
            backgroundColor: '#f08080',
            title: 'Mom Birthday'
        },
        {
            days: [
                ['2019-06-01', '2019-06-14'],
                ['2019-08-16', '2019-04-29']
            ],
            backgroundColor: '#6495ed',
            color: '#fff',
            title: 'Summer Holidays'
        }
    ]
});
```