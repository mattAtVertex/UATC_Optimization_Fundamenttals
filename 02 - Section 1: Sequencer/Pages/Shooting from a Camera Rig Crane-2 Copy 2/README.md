# Shooting from a Camera Rig Crane-2 Copy 2

<p>One of the methods real-world filmmakers use to produce smooth, sweeping shots, is by attaching a camera to a crane and controlling the shot with the crane's movement. You can create similar shots in Sequencer with the use of the<span>&nbsp;</span><strong>Camera Rig Crane</strong><span>&nbsp;</span>Actor and an attached<span>&nbsp;</span><strong>Camera</strong>. You can keyframe the crane's Pitch, Yaw, or the length of the Crane Arm, as well as Lock the Mounted Camera's Pitch or Yaw (which will follow the crane's movement).</p>
<p>In this guide, we will add a Camera Rig Crane, attach a Camera, and create a sample Crane Shot as indicated in the example below:</p>
<p>&nbsp;</p>
<p><span>1. In the Level Viewport of your project, select the&nbsp;</span><strong>ThirdPersonCharacter</strong><span>, then hold&nbsp;</span><strong>Alt</strong><span>, click a translation widget arrow and drag out, then rotate the copy so that it faces the existing character.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/315/files/20650/preview?verifier=BYtrB677BMGJdZf1RzhtmPWFrEzsX4PKiSXDyiDU" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/315/files/20650" data-api-returntype="File"></p>
<p>These two characters are going to be the subject of our crane shot.</p>
<p>&nbsp;</p>
<p><span>2. </span><span>From the Main Toolbar, click the&nbsp;</span><strong>Cinematics</strong><span>&nbsp;button, then select&nbsp;</span><strong>Add Level Sequence</strong><span>&nbsp;from the drop-down menu.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/315/files/20656/preview?verifier=7oFEtJEyEteDdqzO2l83tBz8XTZsB9qp8uWbKAa1" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/315/files/20656" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p>3. From the<span>&nbsp;</span><strong>Place Actors</strong><span>&nbsp;</span>panel in the<span>&nbsp;</span><strong>Cinematic</strong><span>&nbsp;</span>tab, drag a<span>&nbsp;</span><strong>Camera Rig Crane</strong><span>&nbsp;</span>into the level.</p>
<p><img src="https://vertexschool.instructure.com/courses/315/files/20657/preview?verifier=xsvp4IDM88t438042MuC9Ij7XzArf3jMlVBHIfR4" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/315/files/20657" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p>4. <span>From the&nbsp;</span><strong>Place Actors</strong><span>&nbsp;panel in the&nbsp;</span><strong>Cinematic</strong><span>&nbsp;tab, drag a&nbsp;</span><strong>Cine Camera Actor</strong><span>&nbsp;into the level.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/315/files/20504/preview?verifier=bZgt6mdYjtYhnfAiXx60OdKjYD3JaZ2IIZstwXlq" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/315/files/20504" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p>5. In the<span>&nbsp;</span><strong>World Outliner</strong><span>&nbsp;</span>panel, drag the<span>&nbsp;</span><strong>Cine Camera Actor</strong><span>&nbsp;</span>on top of the<span>&nbsp;</span><strong>Camera Rig Crane</strong><span>&nbsp;</span>to attach it.</p>
<p><img src="https://vertexschool.instructure.com/courses/315/files/20505/preview?verifier=HFM7gjBTHMp0IVNdyPzixGfGPpoVh0iVLWzRS3Zb" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/315/files/20505" data-api-returntype="File"></p>
<p>This will attach the camera to the crane, allowing it to move where the crane moves.</p>
<p>&nbsp;</p>
<p>6.&nbsp; In the<span>&nbsp;</span><strong>Details</strong><span>&nbsp;</span>panel for the<span>&nbsp;</span><strong>Cine Camera Actor</strong>, set the<span>&nbsp;</span><strong>Location</strong><span>&nbsp;</span>and<span>&nbsp;</span><strong>Rotation</strong><span>&nbsp;</span>values to<span>&nbsp;</span><strong>0.0</strong>.</p>
<p><img src="https://vertexschool.instructure.com/courses/315/files/20519/preview?verifier=hYG1Ur6exFCs9QcUwhmURUrkFLJqkt8jHp3OYlg4" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/315/files/20519" data-api-returntype="File"></p>
<p>This will allow the camera to be attached to the Camera Rig Crane's mount position.</p>
<p>&nbsp;</p>
<p>7. Make any adjustments to the position of the<span>&nbsp;</span><strong>Camera Rig Crane</strong><span>&nbsp;</span>to set up your shot (below, the position is behind the character).</p>
<p><img src="https://vertexschool.instructure.com/courses/315/files/20555/preview?verifier=buOQ9dhblCskD26Fa3PDxOOVywptOGq4NU7mQZ6A" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/315/files/20555" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p>8. <span>Hold&nbsp;</span><strong>Ctrl</strong><span>&nbsp;and select the&nbsp;</span><strong>Camera Rig Crane</strong><span>&nbsp;and&nbsp;</span><strong>Cine Camera Actor</strong><span>&nbsp;(so that both are selected), then click&nbsp;</span><strong>Add</strong><span>&nbsp;in Sequencer and add both to the Level Sequence.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/315/files/20556/preview?verifier=75Aqn5pB52JncxATyzRD5dZcN61gDtN4D73RFstR" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/315/files/20556" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p><span>9. Select the&nbsp;</span><strong>Camera Rig Crane</strong><span>, then in the&nbsp;</span><strong>Details</strong><span>&nbsp;panel, click the&nbsp;</span><strong>Add Key</strong><span>&nbsp;button for&nbsp;</span><strong>Crane Pitch</strong><span>,&nbsp;</span><strong>Crane Yaw</strong><span>&nbsp;and&nbsp;</span><strong>Crane Arm Length</strong><span>.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/315/files/20557/preview?verifier=YRGzmVnfHxQm7CofSqFJfQVFeRneAFZ1gbIQkhpO" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/315/files/20557" data-api-returntype="File"></p>
<p>This will set the default position of each to start the sequence.</p>
<p>&nbsp;</p>
<p><span>10. In Sequencer, select the&nbsp;</span><strong>Cine Camera Actor</strong><span>, then press the&nbsp;</span><strong>S</strong><span>&nbsp;key.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/315/files/20578/preview?verifier=MccjgBTa2ksnkV5xBVtMjGngQfUbCj9bRfnJkBHE" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/315/files/20578" data-api-returntype="File"></p>
<p><span>This is a shortcut for adding a key for the current&nbsp;</span><strong>Transform</strong><span>&nbsp;values, initializing the camera's position.</span></p>
<p>&nbsp;</p>
<p><span>11. Scrub the Timeline to frame&nbsp;</span><strong>50</strong><span>, changing the&nbsp;</span><strong>Crane Pitch</strong><span>&nbsp;value on the&nbsp;</span><strong>Camera Rig Crane</strong><span>&nbsp;to&nbsp;</span><strong>40.0</strong><span>, and then click the&nbsp;</span><strong>Add Key</strong><span>&nbsp;button.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/315/files/20640/preview?verifier=zyCpmFlYs94izi56RE4FLVfK38ADEY01vNtmo4Hp" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/315/files/20640" data-api-returntype="File"></p>
<p><span>If you move the Timeline back to 0 and scrub through to 50, you will see the crane move between the two keyframes.</span></p>
<p>&nbsp;</p>
<p>12. <span>With the Timeline at frame&nbsp;</span><strong>50</strong><span>, select the&nbsp;</span><strong>Cine Camera Actor</strong><span>, and then press&nbsp;</span><strong>S</strong><span>&nbsp;to add another keyframe.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/315/files/20641/preview?verifier=4dydJOKVldpUTlubKLovOX57PMPJx8dE5a0qA5Ak" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/315/files/20641" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p><span>13. Scrub the Timeline ahead to the end of the shot, change the&nbsp;</span><strong>Crane Yaw</strong><span>&nbsp;and&nbsp;</span><strong>Crane Arm Length</strong><span>&nbsp;to&nbsp;</span><strong>75</strong><span>&nbsp;and&nbsp;</span><strong>600</strong><span>&nbsp;respectively, then add keys for each.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/315/files/20658/preview?verifier=K7YX1zDnNHQEqZsooVoqrTf00lk4Jf5GSeMrvQJF" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/315/files/20658" data-api-returntype="File"></p>
<p>You should see the values shift between keyframes for the Crane Yaw and Crane Arm Length as you scrub through the Timeline.</p>
<div>
<div id="player_d7K3mHA0bXM_386"></div>
</div>
<p>&nbsp;</p>
<p>14. Rotate the camera in the Level Viewport to frame up the two characters, then press<span>&nbsp;</span><strong>S</strong><span>&nbsp;</span>to add a keyframe for the position.</p>
<p><img src="https://vertexschool.instructure.com/courses/315/files/20659/preview?verifier=zgqsM8iGkANf73SmgYIxBsZJTN54PUKE9r1ySFL0" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/315/files/20659" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p><span>15. In Sequencer, click the&nbsp;</span><strong>Camera Lock</strong><span>&nbsp;button on the&nbsp;</span><strong>Cine Camera Actor</strong><span>&nbsp;track.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/315/files/20660/preview?verifier=PktizMDyDm6fiIU45EHFoEmqXAywQO6u7silvnJ4" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/315/files/20660" data-api-returntype="File"></p>
<p><span>This will lock the viewport to the perspective of the camera and allow us to view what the shot will look like when using this camera.</span></p>
<p>&nbsp;</p>
<p>&nbsp;</p>