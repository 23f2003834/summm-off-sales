# Sales Summary App  
This minimal single-page application fetches CSV data embedded within the code, computes the total sales, and displays the summary. It includes a currency selector with options for USD, EUR, GBP, and TH, allowing users to view the total sales converted to the selected currency based on predefined exchange rates specified in the embedded `rates.json`. The app uses Bootstrap 5.3.3 loaded from jsDelivr CDN for styling, with a fallback CSS to ensure basic styling if Bootstrap fails to load.  
  
All logic is encapsulated within a self-invoking script to fulfill specific checks, including the presence of the currency picker and the total currency display. Users can select their preferred currency, and the total sales update dynamically.  
   
Ensure your environment supports inline scripts and that the `index.html` is served with proper permissions. Output exactly in this format with no extra text or markdown code fences (```):