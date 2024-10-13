---
title: 'Data'
date: 2018-11-28T15:14:39+10:00
weight: 1
---

If you want to skip the background for now, go and [download the data]({{< relref "#Download Data" >}}) directly.

This year's competition focuses on computational screening of alloy compositions from scrap metals to enable rapid discovery of new sustainable alloys. Materials research must become faster and more flexible to meet current societal challenges such as climate neutrality by 2050, the European Green Deal for a circular economy, current bottlenecks in raw material supply chains, and rising raw material and energy costs [\[ 1 \]]({{< relref "#References and Acknowledgments" >}}). Recycling offers great potential for the development of new sustainable materials [\[ 2 \]]({{< relref "#References and Acknowledgments" >}}). New alloys can be smelted by suitable combinations of different high-value scrap metals, which can serve as alternatives in the aerospace, power generation or automotive industries. To this end, we are using a simulation-based, high-throughput alloy screening approach, complemented by experimental data and validation, to dramatically accelerate the process of identifying and developing new scrap-based alloys that yield novel, tailored alloy designs with specific properties that can be reintegrated into advanced products and applications.

The data provided for this challenge was generated for the specific use case of developing a new Al-based alloy suitable for additive manufacturing by blending different available aluminum metal scrap such as automotive Al-Si piston alloys [\[ 3, 4, 5 \]]({{< relref "#References and Acknowledgments" >}}) and other alloys from different sectors. Different alloy designs were initially generated based on mixing ratios between available scrap alloys. The CALPHAD method was used to perform equilibrium and non-equilibrium calculations to predict relevant thermo-physical and mechanical variables such as the content of volatile elements like Mg and Zn, phase formation and their fractions, solidification intervals, thermo-physical parameters, yield strength and hot crack sensitivity for each alloy composition.

To evaluate the obtained data, sensitivity analysis is performed to find composition-microstructure-property correlations within these complex material systems. Currently, 2D and 3D plots (line or scatter) are used to visualize and interpret the data in an attempt to find correlations and indicators to identify optimized alloys with appropriate target properties for aerospace applications (e.g. Fig.1).

{{< rawhtml >}}
<img src="/pcp.png" alt="parallel coordinates plot visualizing the information that can be obtained using high-throughput thermodynamic calculations to predict properties." class="matlab">
<p style="color: grey;">Fig.1: parallel coordinates plot visualizing the information that can be obtained using high-throughput thermodynamic calculations to predict properties.</p>
{{< /rawhtml >}}

The challenge in terms of visualization is to develop (novel) visual encodings that can provide valuable insights into abstract material data generated from varying ratios of these alloys and simulating their respective material properties, e.g., in terms of understanding and interpreting data, generating overviews, or revealing interesting input/output areas or individual alloy candidates.



Based on this, we have provided a list of visualization [tasks](/tasks) for this contest.


{{< rawhtml >}}
<div style="height:  20px"></div>
{{< /rawhtml >}} 

----------   

{{< rawhtml >}}
<div style="height:  20px"></div>
{{< /rawhtml >}}