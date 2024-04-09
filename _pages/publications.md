---
title: 
permalink: "/publications/"
layout: archive
author_profile: true
---

## Journal/Conference
<table style="width:100%">
    <thead>
		<tr>
			<th width="20%">Highlight</th>
			<th width="15%">Authors</th>
			<th width="43%">Title</th>
			<th width="2%">Year</th>
			<th width="20%">Journal/Proceedings</th>
		</tr>
    </thead>
	<tbody>
  <tr id="wang2022trustworthy" class="entry">
          <td>
        <div class="polaroid">
          <!-- <img src="" width="600" class="research_img">-->
        </div>
      </td>
          <td><strong>P. Jia</strong>, <br> J. Gong, et al.</td>
      <td>
        Structured Bird's-Eye View Road Scene Understanding from Surround Video<br>
                <p class="infolinks"> 
                  [<a href="javascript:toggleInfo('zhang2023shareable','abstract')">Abstract</a>]
              </p>
        </td>
      <td>2024</td>
      <td>2024 IEEE Intelligent Vehicles Symposium (Accept)</td>
  </tr>
  <tr id="abs_zhang2023shareable" class="abstract noshow">
      <td colspan="5"><div align="justify"> <b>Abstract</b>: Autonomous vehicles require an accurate understanding of the surrounding road scene for navigation. One crucial task in this understanding is the bird's-eye view (BEV) road network estimation. However, accurately extracting the BEV road network around the vehicle in complex scenes, considering variations in lane curvature and shape, remains a challenge. This paper aims to accurately represent and learn the BEV road network around the vehicle for structured road scene understanding. Specifically, we propose a road network representation, i.e., representing the lane centerline as an ordered point set and the road network as a directed graph, which accurately describes lane centerline instances and lane topological relationships in complex scenes. Then, we introduce an online road network estimation framework that takes on-board surround-view video as input and utilizes hierarchical query embedding to extract the BEV road network around the vehicle. Furthermore, we present a temporal aggregation module to alleviate occlusion issues in road scenes and enhance the accuracy of road network estimation by incorporating historical frame information flexibly. Finally, to validate the efficacy of our method for structured BEV road scene understanding, we conduct extensive experiments on the nuScenes dataset. </div>
    </td>
  </tr>
  
  <tr id="zhang2023dataset" class="entry">
          <td>
        <div class="polaroid">
          <!-- <img src="../images/jiapeng.png" width="600" class="research_img">-->
        </div>
      </td>
          <td><strong>P. Jia</strong>, Y. Jiang, et al.</td>
      <td>
        SRSU: An Online Road Map Detection and Network Estimation for Structured Bird's-Eye View Road Scene Understanding <br>
                <p class="infolinks"> 
                  [<a href="javascript:toggleInfo('zhang2023dataset','abstract')">Abstract</a>]
              </p>
        </td>
      <td>2024</td>
      <td>IEEE Transactions on Intelligent Vehicles (Under review)</td>
  </tr>
  <tr id="abs_zhang2023dataset" class="abstract noshow">
      <td colspan="5"><div align="justify"> <b>Abstract</b>: However, considering the flexibility of autonomous vehicles and the variations in lane curvature and shape, the online and accurate extraction of road maps with fine-grained boundaries and road networks with lane topology in a unified framework remains challenging. This paper proposes SRSU, an online road map detection and network estimation framework for structured bird's-eye view road scene understanding. Specifically, we introduce a hierarchical map representation, \emph{i.e.}, representing the road map as a set of ordered point sets with equivalent permutations and the road network as a directed graph, accurately describing the fine-grained map boundaries and lane topology in a unified framework. Building upon the above representation, we propose an online hierarchical map construction framework. It utilizes two sets of learnable hierarchical query embeddings to extract road maps with fine-grained boundaries and road networks with lane topologies, achieving a comprehensive understanding of the road scene. Furthermore, we introduce three empirical modules to enhance the accuracy of hierarchical map construction. These modules are termed auxiliary task prediction, multi-modal distillation, and higher-order interaction, responsible for enhancing the model's representational capabilities and providing valuable auxiliary information for subsequent tasks, generating robust features for final tasks, and learning the association information between different tasks, respectively. Finally, experiments on the nuScenes dataset demonstrate the proposed framework's effectiveness while highlighting the empirical module's superiority. Code will be available at \href{https://github.com/jiapeng789/SRSU}{https://github.com/jiapeng789/SRSU}.</div>
    </td>
   </tr>
 
	</tbody>
</table>

