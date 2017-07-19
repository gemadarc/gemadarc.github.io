---
---

# Facilities and Labs
  <p>Every institution in GEMADARC has unique labs and facilities that are involved in germanium related research. </p>

  <ul class="nav nav-tabs">
    <li class="active"><a data-toggle="tab" href="#home">USD</a></li>
    <li><a data-toggle="tab" href="#menu1">UNC</a></li>
    <li><a data-toggle="tab" href="#menu2">TAMU</a></li>
    <li><a data-toggle="tab" href="#menu3">LBNL</a></li>
	<li><a data-toggle="tab" href="#menu4">BHSU</a></li>
	<li><a data-toggle="tab" href="#menu5">UMN</a></li>
	<li><a data-toggle="tab" href="#menu6">TTU</a></li>
	<li><a data-toggle="tab" href="#menu7">Queen's</a></li>
	<li><a data-toggle="tab" href="#menu8">Tsinghua</a></li>
	<li><a data-toggle="tab" href="#menu9">MPI</a></li>
	<li><a data-toggle="tab" href="#menu10">IOP-AS</a></li>
  </ul>

  <div class="tab-content">
    <div id="home" class="tab-pane fade in active">
	{% capture my_include %}{% include_relative /usd.md %}{% endcapture %}
	{{ my_include | markdownify }}
    </div>
    <div id="menu1" class="tab-pane fade">
	{% capture my_include %}{% include_relative /unc.md %}{% endcapture %}
	{{ my_include | markdownify }}

    </div>
    <div id="menu2" class="tab-pane fade">
	{% capture my_include %}{% include_relative /tamu.md %}{% endcapture %}
	{{ my_include | markdownify }}
    
    </div>
    <div id="menu3" class="tab-pane fade">
	{% capture my_include %}{% include_relative /lbnl.md %}{% endcapture %}
	{{ my_include | markdownify }}    
    </div>
	<div id="menu4" class="tab-pane fade">
	{% capture my_include %}{% include_relative /bhsu.md %}{% endcapture %}
	{{ my_include | markdownify }}    
    </div>
    <div id="menu5" class="tab-pane fade">
	{% capture my_include %}{% include_relative /umn.md %}{% endcapture %}
	{{ my_include | markdownify }}    
    </div>
    <div id="menu6" class="tab-pane fade">
	{% capture my_include %}{% include_relative /ttu.md %}{% endcapture %}
	{{ my_include | markdownify }}    
    </div>
    <div id="menu7" class="tab-pane fade">
	{% capture my_include %}{% include_relative /queens.md %}{% endcapture %}
	{{ my_include | markdownify }}    
    </div>
    <div id="menu8" class="tab-pane fade">
	{% capture my_include %}{% include_relative /tsinghua.md %}{% endcapture %}
	{{ my_include | markdownify }}    
    </div>
    <div id="menu9" class="tab-pane fade">
 	{% capture my_include %}{% include_relative /mpi.md %}{% endcapture %}
	{{ my_include | markdownify }}   
    </div>
    <div id="menu10" class="tab-pane fade">
 	{% capture my_include %}{% include_relative /iopas.md %}{% endcapture %}
	{{ my_include | markdownify }}   
    </div>
	
  </div>