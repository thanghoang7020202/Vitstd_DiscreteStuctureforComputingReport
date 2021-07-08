# COVID-19 forecasting by *Vitstd* (MODEL 2)

### 🗂️ Download complete COVID-19 dataset: [CSV](http://www.serverless.com) | [XLSX](https://covid.ourworldindata.org/data/owid-covid-data.xlsx)
The complete dataset is a collection of the COVID-19 data maintained by [Our World in Data](https://ourworldindata.org/coronavirus). You can find out more about the dataset in this [github repo](https://github.com/owid/covid-19-data).

## ⭐ Try out our models:

<details>
  <summary> <strong> Multi-gaussian model </strong> </summary>
    <ol>
      <li> Visit our <a href="https://colab.research.google.com/drive/1DsFaJV6vrwJRbxK4Ntq54PPTm3emHFVm?usp=sharing">Colab Notebook</a>. </li>
      <li> Input <code>location</code> and <code>number_of_days</code> to perform analysis and forecasting </li>
      <li> Press <code>Ctrl+F9</code> to run. </li>
      <li> Results will be save in <code>fig</code> folder, including: </li>
        <ul>
          <li> New cases: <code> fig/&lt;location&gt-newCases.png </code> </li>
          <li> Total cases: <code> fig/&lt;location&gt-totalCases.png </code> </li>
          <li> Moving average: <code> fig/&lt;location&gt-movingAverage.png </code> </li>
          <li> Log new cases to total cases: <code> fig/&lt;location&gt-Log.png </code> </li>
          <li> Gaussian fitting and prediction: <code> fig/&lt;location&gt-fitGaussian.png </code> </li>
        </ul>
    </ol>
</details>
