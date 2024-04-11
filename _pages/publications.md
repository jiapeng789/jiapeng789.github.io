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
          <td><strong>P. Jia</strong>, <br> J. Gong, <br> et al.</td>
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
          <td><strong>P. Jia</strong>, <br> Y. Jiang, <br> et al.</td>
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
      <td colspan="5"><div align="justify"> <b>Abstract</b>: Autonomous driving requires a structured understanding of the surrounding road maps and networks to navigate. However, considering the flexibility of autonomous vehicles and the variations in lane curvature and shape, the online and accurate extraction of road maps with fine-grained boundaries and road networks with lane topology in a unified framework remains challenging. This paper proposes SRSU, an online road map detection and network estimation framework for structured bird's-eye view road scene understanding. Specifically, we introduce a hierarchical map representation, i.e., representing the road map as a set of ordered point sets with equivalent permutations and the road network as a directed graph, accurately describing the fine-grained map boundaries and lane topology in a unified framework. Building upon the above representation, we propose an online hierarchical map construction framework. It utilizes two sets of learnable hierarchical query embeddings to extract road maps with fine-grained boundaries and road networks with lane topologies, achieving a comprehensive understanding of the road scene. Furthermore, we introduce three empirical modules to enhance the accuracy of hierarchical map construction. These modules are termed auxiliary task prediction, multi-modal distillation, and higher-order interaction, responsible for enhancing the model's representational capabilities and providing valuable auxiliary information for subsequent tasks, generating robust features for final tasks, and learning the association information between different tasks, respectively. Finally, experiments on the nuScenes dataset demonstrate the proposed framework's effectiveness while highlighting the empirical module's superiority. </div>
    </td>
   </tr>

   <tr id="jia2024dataset" class="entry">
          <td>
        <div class="polaroid">
          <!-- <img src="../images/jiapeng.png" width="600" class="research_img">-->
        </div>
      </td>
          <td><strong>P. Jia</strong>, <br> Z. Ju, <br> et al.</td>
      <td>
        An Online Environment Perception Framework with Multi-Level Information Fusion and Bird's-Eye View Representation <br>
                <p class="infolinks"> 
                  [<a href="javascript:toggleInfo('jia2024dataset','abstract')">Abstract</a>]
              </p>
        </td>
      <td>2024</td>
      <td>Automobile Innovation (Under review)</td>
  </tr>
  <tr id="abs_jia2024dataset" class="abstract noshow">
      <td colspan="5"><div align="justify"> <b>Abstract</b>: Autonomous driving requires to accurately perception the surrounding 3D objects and road maps to navigation. Existing methods utilize multi-modal sensors to online detect surrounding 3D objects and obtain road maps from offline HD maps, realizing the perception of the road environment around the vehicle. However, these methods still face challenges in improving perception accuracy and reducing operating costs. In this paper, we propose an online environment perception framework based on multi-level information fusion and bird's-eye view representation. It takes on-board multi-modal sensors as inputs, explores multi-level information fusion and multi-task learning mechanisms, detecting 3D objects and road maps in a unified framework to realize the online perception of the road environment. Specifically, we propose the CBT module, which utilizes the depth information of LiDAR point clouds to guide the prediction of image depth, improving the representation capability of the camera encoder. Then, we propose the RAFD module, which employs the local semantics of the image to decorate the LiDAR points, improving the representation capability of the LiDAR encoder. Thirdly, we introduce the MFAF module, which uses the attention mechanism to fuse the complementary features of multi-modal sensors, generating robust BEV features for the final task. Furthermore, we jointly perform 3D object detection and road map estimation on BEV features to achieve the perception of the road environment online in a unified framework. Finally, experiments on the nuScenes dataset demonstrate the proposed method achieves online, accurate, and robust perception in both normal and harsh scenes. </div>
    </td>
   </tr>
 
	</tbody>
</table>

