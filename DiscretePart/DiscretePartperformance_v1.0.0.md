# Table of performance results for Discrete part
Model | dataset |  DP classes | input size | output size |train acc | test acc | code tag
--- | --- | --- | --- | --- | --- | --- | --- 
2_Dense|MNIST|<table><thead>  <tr>  <th> Class </th>  <th>Values</th>  </tr>  </thead><tbody><tr><td>0</td> <td>[0]</td></tr><tr><td>1</td> <td>251-255</td></tr></tbody></table>|784|10|0.43|0.46|V1.0.0
conv|MNIST|<table><thead>  <tr>  <th> Class </th>  <th>Values</th>  </tr>  </thead><tbody><tr><td>0</td> <td>[0]</td></tr><tr><td>1</td> <td>251-255</td></tr></tbody></table>|784|10|1.00|0.98|V1.0.0
2_Dense|fashionMNIST|<table><thead>  <tr>  <th> Class </th>  <th>Values</th>  </tr>  </thead><tbody><tr><td>0</td> <td>0-3</td></tr><tr><td>1</td> <td>[255]</td></tr></tbody></table>|784|10|0.94|0.85|V1.0.0
conv|fashionMNIST|<table><thead>  <tr>  <th> Class </th>  <th>Values</th>  </tr>  </thead><tbody><tr><td>0</td> <td>0-3</td></tr><tr><td>1</td> <td>[255]</td></tr></tbody></table>|784|10|0.91|0.85|V1.0.0
2_Dense|breast_medMNIST|<table><thead>  <tr>  <th> Class </th>  <th>Values</th>  </tr>  </thead><tbody></tbody></table>|784|2|0.00|0.00|V1.0.0
conv|breast_medMNIST|<table><thead>  <tr>  <th> Class </th>  <th>Values</th>  </tr>  </thead><tbody></tbody></table>|784|2|0.00|0.00|V1.0.0
2_Dense|organs_medMNIST|<table><thead>  <tr>  <th> Class </th>  <th>Values</th>  </tr>  </thead><tbody><tr><td>0</td> <td>[0]</td></tr><tr><td>1</td> <td>[255]</td></tr></tbody></table>|784|11|0.93|0.46|V1.0.0
conv|organs_medMNIST|<table><thead>  <tr>  <th> Class </th>  <th>Values</th>  </tr>  </thead><tbody><tr><td>0</td> <td>[0]</td></tr><tr><td>1</td> <td>[255]</td></tr></tbody></table>|784|11|0.73|0.48|V1.0.0
2_Dense|pneumonia_medMNIST|<table><thead>  <tr>  <th> Class </th>  <th>Values</th>  </tr>  </thead><tbody></tbody></table>|784|2|0.00|0.00|V1.0.0
conv|pneumonia_medMNIST|<table><thead>  <tr>  <th> Class </th>  <th>Values</th>  </tr>  </thead><tbody></tbody></table>|784|2|0.00|0.00|V1.0.0
2_Dense|oct_medMNIST|<table><thead>  <tr>  <th> Class </th>  <th>Values</th>  </tr>  </thead><tbody><tr><td>0</td> <td>4-95</td></tr><tr><td>1</td> <td>253-255</td></tr></tbody></table>|784|4|0.58|0.38|V1.0.0
conv|oct_medMNIST|<table><thead>  <tr>  <th> Class </th>  <th>Values</th>  </tr>  </thead><tbody><tr><td>0</td> <td>4-95</td></tr><tr><td>1</td> <td>253-255</td></tr></tbody></table>|784|4|0.79|0.53|V1.0.0
2_Dense|tissue_medMNIST|<table><thead>  <tr>  <th> Class </th>  <th>Values</th>  </tr>  </thead><tbody><tr><td>0</td> <td>0-75</td></tr></tbody></table>|784|8|0.36|0.37|v1.0.0
conv|tissue_medMNIST|<table><thead>  <tr>  <th> Class </th>  <th>Values</th>  </tr>  </thead><tbody><tr><td>0</td> <td>0-75</td></tr></tbody></table>|784|8|0.45|0.42|v1.0.0
