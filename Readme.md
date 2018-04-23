# How to provide a custom template for series labels


<p>The following example demonstrates how to change the appearance of <a href="https://documentation.devexpress.com/#WPF/CustomDocument6341">series labels</a>.<br /><br />To accomplish this, it is necessary to create a <strong>System.Windows.DataTemplate</strong> that specifies the appearance of series labels, and add it to a window's resource. Then, this template can be applied to a series label via its <a href="http://larix/ReferenceBrowserMain_14_2/LoadItem.aspx?Member=P%3aDevExpress.Xpf.Charts.ChartTextElement.ElementTemplate&Template=MemberPropertyTopic">ChartTextElement.ElementTemplate</a> property.<br /><br /><strong>Note</strong> that  the chart control displays a <a href="https://documentation.devexpress.com/#WPF/CustomDocument11974">crosshair cursor</a>  instead of series labels in the diagram by default. <br />To provide series labels customization, enable series labels (set the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfChartsSeries_LabelsVisibilitytopic">Series.LabelsVisibility</a> property to <strong>true</strong>). if you wish you can disable  the crosshair cursor (set the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfChartsChartControl_CrosshairEnabledtopic">ChartControl.CrosshairEnabled</a> property to<strong> false</strong>). </p>


<h3>Description</h3>

<p>For this, it is necessary to create a <strong>DataTemplate</strong>, which specifies the appearance of series labels, and add it to a window&#39;s resource. Then, this template can be applied to a series label via its <strong>SeriesLabel.Template</strong> property.</p>

<br/>


