IHighDefinitionFaceFrameSource::UnsubscribeTrackingIdLost Method  
================================================================  

Unsubscribes the specified event handler that processes new frames. <span id="syntaxSection"></span>

Syntax  
======  

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C++</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public:  
HRESULT UnsubscribeTrackingIdLost(  
         WAITABLE_HANDLE waitableHandle  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[in] The handle to the subscribed event handler.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : UnsubscribeTrackingIdLost Method
RLTitle : IHighDefinitionFaceFrameSource::UnsubscribeTrackingIdLost Method
KeywordK : UnsubscribeTrackingIdLost method
KeywordK : IHighDefinitionFaceFrameSource::UnsubscribeTrackingIdLost method
KeywordF : IHighDefinitionFaceFrameSource::UnsubscribeTrackingIdLost
KeywordF : UnsubscribeTrackingIdLost
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.UnsubscribeTrackingIdLost(WAITABLE_HANDLE)
KeywordA : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.UnsubscribeTrackingIdLost(WAITABLE_HANDLE)
AssetID : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.UnsubscribeTrackingIdLost(WAITABLE_HANDLE)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource::UnsubscribeTrackingIdLost
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
