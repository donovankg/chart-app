## Chart App
#https://donovankg.github.io/chart-app/
This app used handsontable and chartjs (can be added with bower).

When the app loads an object is created with handsontable and then the data is 
put into arrays so they chart can read them. When a field in the table is
changed, the chart changes using the "aftercharge" to trigger the event
on the table then the chart uses the update function that comes with chart.js.
