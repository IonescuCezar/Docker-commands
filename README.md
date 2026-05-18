**Dockerfile** contains the instructions to build a Docker image;<br />
&nbsp;&nbsp;&nbsp; *recipe / blueprint of construction<br />

**Docker image** represents the object that is constructed by executing instructions from the Dockerfile;<br />
&nbsp;&nbsp;&nbsp; *a Docker image is **immutable**<br />

**Docker container** represents a **running instance** of a Docker image;<br /><br />

Commands:<br />
&nbsp;&nbsp;&nbsp; • docker **pull** { image_name }**:**{ image_tag }

&nbsp;&nbsp;&nbsp; • docker **images**

&nbsp;&nbsp;&nbsp; • docker **ps**<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *ps means *process status*

&nbsp;&nbsp;&nbsp; • docker **ps** **--all**<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; docker **ps** **-a**

&nbsp;&nbsp;&nbsp; • docker **run** { image_name }**:**{ image_tag }

&nbsp;&nbsp;&nbsp; • docker **run** **--detach** { image_name }**:**{ image_tag }<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; docker **run** **-d** { image_name }**:**{ image_tag }

&nbsp;&nbsp;&nbsp; • docker **run** **--publish** { host_port }**:**{ container_port } { image_name }**:**{ image_tag }<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; docker **run** **-p** { host_port }**:**{ container_port } { image_name }**:**{ image_tag }

&nbsp;&nbsp;&nbsp; • docker **run** **--name** { assigned_container_name } { image_name }**:**{ image_tag }

&nbsp;&nbsp;&nbsp; • docker **logs** { short_id_container }

&nbsp;&nbsp;&nbsp; • docker **stop** { short_id_container }

&nbsp;&nbsp;&nbsp; • docker **start** { short_id_container }
