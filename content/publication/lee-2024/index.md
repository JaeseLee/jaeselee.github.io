---
title: Improved SMAP Soil Moisture Retrieval Using a Deep Neural Network-Based Replacement
  of Radiative Transfer and Roughness Model
authors:
- Jaese Lee
- Jungho Im
- Bokyung Son
- Eric G. Cosio
- Norma Salinas
date: '2024-01-01'
publishDate: '2025-01-10T15:07:15.997779Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Geoscience and Remote Sensing*'
doi: 10.1109/TGRS.2024.3489974
abstract: The L-band (1.4 GHz) brightness temperature (TB) is interpreted by the zeroth-order
  approximation of the radiation transfer model, known as the $τ$ - $ømega$ model.
  The soil moisture active passive (SMAP) mission facilitates the operational retrieval
  of global soil moisture (SM) through the $τ$ - $ømega$ model. The operational SMAP
  SM retrieval algorithms demonstrate favorable alignment with the International SM
  Network (ISMN) and the SMAP core validation sites (CVSs). Nevertheless, the performance
  of these retrieval algorithms is reduced in densely vegetated areas or on rough
  surfaces, due to the smaller sensitivity of L-band TB to SM and less optimized parameterization.
  Therefore, this study proposed a deep neural network (DNN) model that can replace
  the currently used algorithms. The complex dielectric constant was simulated using
  ISMN data with the dielectric model to directly train DNN and determine the relationship
  between measured TB and retrieved dielectric constant. This involved establishing
  a correlation between the measured V- and H-polarized TB and the parameters from
  the SMAP SCA, i.e., surface temperature, vegetation water content (VWC), b, $ømega$
  , and h. The challenge posed by the scale mismatch between point-based and SM data
  was effectively managed using the triple collocation analysis (TCA). The accuracy
  of the proposed model was evaluated using the ISMN and SMAP CVS and compared with
  the existing SM retrievals such as SCA-V, DCA, SMAP-IB, and the recently developed
  MCCA. The developed SM in this study demonstrated enhanced agreement with ISMN,
  SMAP CVS in situ SM data, and the Tambopata site located in the Amazon compared
  with existing SM retrievals. Moreover, by inversely tracking the developed DNN,
  we propose a novel method for parameterizing the $τ$ - $ømega$ model that potentially
  improves the parameterization of the existing SMAP-based SM retrieval algorithms.
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/10741325/
---
