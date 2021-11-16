# Shredder-Machine-Hand-Detection

Consumer Product Safety Commission data indicate that over 2,000 people were treated in hospitals for business and office machine injuries during 2007. Lacerations to fingers from paper shredders and other shredder accidents were among these injuries. Most injuries were caused by operator inattention or error. 

As an Attempt to solve the above problem this project was developed to alert  when the hand moves beyond a certain limit into the shredder machine. When the hand is reaching near the blades of the machine and  cross the second threshold the machine is set to auto cutoff. 

The model is trained on SSD mobile net, the data was collected from a recording  of 24 hours of workers working with the shredder. The data was then augmented and validated using Data augmentation techniques. The data was then annotated and trained using faster RCNN and Mobilenet SSD model, as Mobile net gave better results it was chosen for productionizing.The code is available in master branch of the repository.

Link : https://youtu.be/c-FHAQso9QU


# Mobilenet-SSD

The mobilenet-ssd model is a Single-Shot multibox Detection (SSD) network intended to perform object detection. This model is implemented using the Caffe* framework. 

<table class="table">
<colgroup>
<col style="width: 50%">
<col style="width: 50%">
</colgroup>
<thead>
<tr class="row-odd"><th class="head"><p>Metric</p></th>
<th class="head"><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="row-even"><td><p>Type</p></td>
<td><p>Detection</p></td>
</tr>
<tr class="row-odd"><td><p>GFLOPs</p></td>
<td><p>2.316</p></td>
</tr>
<tr class="row-even"><td><p>MParams</p></td>
<td><p>5.783</p></td>
</tr>
<tr class="row-odd"><td><p>Source framework</p></td>
<td><p>Caffe*</p></td>
</tr>
</tbody>
</table>


<h2>Accuracy<a class="headerlink" href="#accuracy" title="Permalink to this headline">¶</a></h2>

<table class="table">
<colgroup>
<col style="width: 50%">
<col style="width: 50%">
</colgroup>
<thead>
<tr class="row-odd"><th class="head"><p>Metric</p></th>
<th class="head"><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="row-even"><td><p>mAP</p></td>
<td><p>67.00%</p></td>
</tr>
</tbody>
</table>
