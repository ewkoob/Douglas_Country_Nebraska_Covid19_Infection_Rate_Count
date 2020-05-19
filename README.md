# Douglas_Country_Nebraska_Covid19_Infection_Rate_Count
manually entering historical screen shot data for Douglas County Nebraska to view Covid 19 Infection Rate trends - 

<a href="https://covidtracking.com/data/state/nebraska" target="_blank" rel="noopener noreferrer">Covid Tracking - Nebraska</a>

<a href="https://www.arcgis.com/apps/opsdashboard/index.html#/21bec056a9a6449abcca89a329868fd6" target="_blank" rel="noopener noreferrer">OPS Dashboard</a>


showdown.extension('targetlink', function() {
  return [{
    type: 'html',
    regex: /(<a [^>]+?)(>.*<\/a>)/g,
    replace: '$1 target="_blank"$2'
  }];
});



