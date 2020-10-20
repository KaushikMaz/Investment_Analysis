<h1>Project Brief</h1>
<p>Tev, an asset management company, wants to make investments in a few companies. The CEO of Tev wants to understand the global trends in investments so that she can take the investment decisions effectively.</p>
<h2>Business and Data Understanding</h2>
<p>Teclov has two minor constraints for investments:<br>
<ol><li>It wants to invest between <strong>5 to 15 million USD</strong> per round of investment</li>
  <li>It wants to invest only in <strong>English-speaking countries</strong> because of the ease of communication with the companies it would invest in</li>
<ul>
<li>For the analysis, consider a country to be English speaking only if English is one of the official languages in that country</li></ul></p>
<p><h3><strong>What is the strategy?</strong></h3>
Tev wants to invest where most other investors are investing. This pattern is often observed among early stage startup investors.</p>
<p/><h3><strong> Where did we get the data from?</strong></h3>
We have taken real investment data from <strong>crunchbase.com</strong>, so the insights we get may be incredibly useful. </p>
<h3>What is Tev’ business objective?</h3>
<p>The business objectives and goals of data analysis are pretty straightforward.<br>
<ol><li><em>Business objective:</em> The objective is to identify the best sectors, countries, and a suitable investment type for making investments. The overall strategy is
to invest where others are investing, implying that the 'best' sectors and countries are the ones 'where most investors are investing'.</li>
  <li><em>Goals of data analysis:</em> The goals are divided into three sub-goals:
    <ul><li><em>Investment type analysis:</em> Comparing the typical investment amounts in the venture, seed, angel, private equity etc. so that Tev can choose the type that is best suited for their strategy.</li>
      <li><em>Country analysis:</em> Identifying the countries which have been the most heavily invested in the past. These will be Tev’ favourites as well.</li>
      <li><em>Sector analysis:</em> Understanding the distribution of investments across the eight main sectors. (Note that we are interested in the eight 'main sectors' provided in the mapping file. The two files — <strong>companies</strong> and <strong>rounds2</strong> — have numerous sub-sector names; hence, we will need to map each sub-sector to its main sector.)</li></ul>
<ul><li><em> Company details:</em> <strong>companies</strong>: A table with basic data of companies</ul></li>
  <li><em>Sector Classification:</em> <strong>mapping.csv</strong>: This file maps the numerous category names in the companies table (such 3D printing, aerospace, agriculture, etc.) to eight broad sector names. The purpose is to simplify the analysis into eight sector buckets, rather than trying to analyse hundreds of them.</li></ol></p>
