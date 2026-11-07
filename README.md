function dailyLog225() {
  const visitors = {
    totalVisits: 1250,
    uniqueVisitors: 870,
    returningVisitors: 380
  };

  console.log("Daily Website Visitor Report");
  console.log("-----------------------------");
  console.log(`Total Visits: ${visitors.totalVisits}`);
  console.log(`Unique Visitors: ${visitors.uniqueVisitors}`);
  console.log(`Returning Visitors: ${visitors.returningVisitors}`);
}

dailyLog225();
