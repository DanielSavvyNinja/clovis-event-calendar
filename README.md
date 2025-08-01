<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Clovis Chamber Event Calendar</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    html, body {
      margin: 0;
      padding: 0;
      font-family: sans-serif;
      background: #f9f9f9;
      height: 100%;
    }
    .container {
      padding: 10px;
      box-sizing: border-box;
      min-height: 100vh;
    }
    h3 {
      margin: 10px 10px 20px;
    }
    #mni-calendar-1754019057802 {
      margin-bottom: 0 !important;
    }
  </style>
</head>
<body>
  <div class="container">
    <h3>Clovis Chamber Events Calendar</h3>
    <div id="mni-calendar-1754019057802"></div>
  </div>

  <script type="text/javascript" src="https://business.clovischamber.com/Content/Script/Calendar.min.js"></script>
  <script type="text/javascript">
    new MNI.Widgets.Calendar("mni-calendar-1754019057802", {
      showLinks: true,
      popUp: true,
      headerFormat: "MMMM yyyy",
      weekdayFormat: "ddd",
      styleTemplate: `#@id .mn-widget-calendar {
        color: #666666;
        font-family: "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif;
        font-size: 16px;
        float: left;
        line-height: 150%;
        text-align: center;
        width: 100%;
      }
      #@id .mn-widget-calendar a {
        color: #6E9934;
        font-weight: 700;
        text-decoration: none;
      }
      #@id .mn-widget-calendar a:hover {
        color: #58A4B0;
      }
      #@id .mn-widget-calendar-clear {
        clear: both;
      }
      #@id .mn-widget-calendar-header {
        font-weight: 700;
        text-align: center;
        text-transform: uppercase;
      }
      #@id .mn-widget-calendar-prev {
        float: left;
      }
      #@id .mn-widget-calendar-next {
        float: right;
      }
      #@id .mn-widget-calendar-weekday,
      .mn-widget-calendar-day {
        display: inline-block;
        width: 14.285714285714286%;
      }
      #@id .mn-widget-calendar-day-prev,
      #@id .mn-widget-calendar-day-next {
        color: #999999;
      }`
    }).create();
  </script>
</body>
</html>
