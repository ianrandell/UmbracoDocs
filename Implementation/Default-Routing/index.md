#Implementation
Get an overview of how the Umbraco pipeline is structured. See what happens from user request to content delivery.

<div class="row implementation">
	<div class="col-sm-12"></div>
</div>

<div class="row">
	<div class="col-xs-3 point">

	</div>
	<div class="col-xs-3">
		<span class="dot big icon-Download">
			<span class="line v-line"></span>
			<span class="line h-line"></span>
		</span>
	</div>
	<div class="col-xs-9">
		<div class="row explain">
			<div class="col-xs-12">
				<h4 class="text-right">User Request</h4>
				<small>A front-end request is made...</small>
			</div>			
		</div>
	</div>
</div>

<div class="row">
	<div class="col-xs-3">
		<span class="dot big icon-Tactics">
			<span class="line v-line top"></span>
			<span class="line v-line"></span>
			<span class="line h-line"></span>
		</span>
		<span class="dot small">
			<span class="line v-line"></span>
			<span class="line h-line"></span>
		</span>
		<span class="dot small">
			<span class="line v-line"></span>
			<span class="line h-line"></span>
		</span>
	</div>
	
	<div class="col-xs-9">
		<div class="row explain">
			<div class="col-xs-12">
				<h4 class="text-right"><a href="Routing/">Routing</a></h4>
				<small>Matching a URL to content</small>
			</div>			
			<div class="col-xs-6">
				<h5><a href="Routing/Pipeline/">Pipeline</a></h5>
				<small>Find document with the request pipeline</small>
			</div>
			<div class="col-xs-6">
				<h5><a href="Routing/MVC/">Render Controller</a></h5>
				<small>Match an MVC controller and action to handle the request</small>
			</div>
		</div>
	</div>
</div>

<div class="row">
	<div class="col-xs-3">
		<span class="dot big icon-Flash">
			<span class="line v-line top"></span>
			<span class="line v-line"></span>
			<span class="line h-line"></span>
		</span>
	</div>
	<div class="col-xs-9">
		<div class="row explain">
			<div class="col-xs-12">
				<h4 class="text-right">Execute request</h4>
				<small>The MVC Action and View are executed</small>
			</div>			
		</div>
	</div>
</div>

<div class="row">
	<div class="col-xs-3">
		<span class="dot big icon-Server-alt">
			<span class="line v-line top"></span>
			<span class="line v-line"></span>
			<span class="line h-line"></span>
		</span>
		<span class="dot small">
			<span class="line v-line"></span>
			<span class="line h-line"></span>
		</span>
	</div>
	
	<div class="col-xs-9">
		<div class="row explain">
			<div class="col-xs-12">
				<h4><a href="Query-Data/">Querying Published Data</a></h4>
				<small>Working with published data during request execution</small>
			</div>
			<div class="col-xs-6">
				<h5><a href="../Reference/Querying/IPublishedContent/">IPublishedContent</a></h5>
				<small>IPublishedContent is the underlying model used in all Umbraco views</small>
			</div>
			<div class="col-xs-6">
				<h5><a href="../Reference/Querying/DynamicPublishedContent/">DynamicPublishedContent</a></h5>
				<small>The dynamic version of IPublishedContent that can be used in all Umbraco views</small>
			</div>
			<div class="col-xs-6">
				<h5><a href="../Reference/Querying/UmbracoHelper/">UmbracoHelper</a></h5>
				<small>Use UmbracoHelper to query published media and content</small>
			</div>
			<div class="col-xs-6">
				<h5><a href="../Reference/Querying/MembershipHelper/">Members</a></h5>
				<small>This section covers the MembershipHelper</small>
			</div>
		</div>
	</div>
</div>

<div class="row">
	<div class="col-xs-3">
		<span class="dot big icon-Article">
			<span class="line v-line top"></span>
			<span class="line v-line"></span>
			<span class="line h-line"></span>
		</span>
	</div>
	<div class="col-xs-9">
		<div class="row explain">
			<div class="col-xs-12">
				<h4 class="text-right">Content is delivered</h4>
			</div>			
		</div>
	</div>
</div>