<svelte:head>
	<title>Quality Assurance - Why It Matters</title>
	<meta name="description" content="Learn about quality assurance, its importance, and best practices for delivering high-quality software products." />
</svelte:head>

<div class="min-h-screen bg-gradient-to-br from-slate-900 via-purple-900 to-slate-900">
	<!-- Hero Section -->
	<header class="relative overflow-hidden">
		<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-24">
			<div class="text-center">
				<h1 class="text-5xl md:text-6xl font-bold text-white mb-6">
					Quality <span class="text-purple-400">Assurance</span>
				</h1>
				<p class="text-xl text-gray-300 max-w-3xl mx-auto mb-8">
					Building trust through excellence. Quality assurance is not just about finding bugs—it's about delivering products that exceed expectations.
				</p>
				<div class="flex justify-center gap-4">
					<a href="#why-qa" class="bg-purple-600 hover:bg-purple-700 text-white font-semibold py-3 px-8 rounded-lg transition-colors">
						Learn More
					</a>
				</div>
			</div>
		</div>
	</header>

	<!-- Why QA Section -->
	<section id="why-qa" class="py-20 bg-slate-800/50">
		<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
			<h2 class="text-4xl font-bold text-white text-center mb-16">Why Quality Assurance Matters</h2>
			<div class="grid md:grid-cols-3 gap-8">
				<div class="bg-slate-800 rounded-xl p-8 border border-purple-500/20 hover:border-purple-500/50 transition-colors">
					<div class="w-14 h-14 bg-purple-600 rounded-lg flex items-center justify-center mb-6">
						<svg class="w-7 h-7 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
							<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
						</svg>
					</div>
					<h3 class="text-xl font-semibold text-white mb-4">Prevents Costly Errors</h3>
					<p class="text-gray-400">
						Finding and fixing bugs early in development is significantly cheaper than addressing them after release. QA saves money and resources in the long run.
					</p>
				</div>
				<div class="bg-slate-800 rounded-xl p-8 border border-purple-500/20 hover:border-purple-500/50 transition-colors">
					<div class="w-14 h-14 bg-purple-600 rounded-lg flex items-center justify-center mb-6">
						<svg class="w-7 h-7 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
							<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z"></path>
						</svg>
					</div>
					<h3 class="text-xl font-semibold text-white mb-4">Ensures Security</h3>
					<p class="text-gray-400">
						QA processes identify security vulnerabilities before they can be exploited, protecting both your business and your customers' sensitive data.
					</p>
				</div>
				<div class="bg-slate-800 rounded-xl p-8 border border-purple-500/20 hover:border-purple-500/50 transition-colors">
					<div class="w-14 h-14 bg-purple-600 rounded-lg flex items-center justify-center mb-6">
						<svg class="w-7 h-7 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
							<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14.828 14.828a4 4 0 01-5.656 0M9 10h.01M15 10h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
						</svg>
					</div>
					<h3 class="text-xl font-semibold text-white mb-4">Builds Customer Trust</h3>
					<p class="text-gray-400">
						Consistent quality creates satisfied customers who become loyal advocates for your brand. Trust is the foundation of lasting business relationships.
					</p>
				</div>
			</div>
		</div>
	</section>

	<!-- QA Process Section -->
	<section class="py-20">
		<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
			<h2 class="text-4xl font-bold text-white text-center mb-16">The QA Process</h2>
			<div class="space-y-8">
				<div class="flex flex-col md:flex-row items-center gap-8">
					<div class="w-16 h-16 bg-purple-600 rounded-full flex items-center justify-center text-2xl font-bold text-white shrink-0">1</div>
					<div class="flex-1 bg-slate-800/50 rounded-xl p-6 border border-slate-700">
						<h3 class="text-xl font-semibold text-white mb-2">Requirements Analysis</h3>
						<p class="text-gray-400">Understanding what needs to be built and defining clear, testable criteria for success.</p>
					</div>
				</div>
				<div class="flex flex-col md:flex-row items-center gap-8">
					<div class="w-16 h-16 bg-purple-600 rounded-full flex items-center justify-center text-2xl font-bold text-white shrink-0">2</div>
					<div class="flex-1 bg-slate-800/50 rounded-xl p-6 border border-slate-700">
						<h3 class="text-xl font-semibold text-white mb-2">Test Planning</h3>
						<p class="text-gray-400">Creating comprehensive test strategies and detailed test cases that cover all scenarios.</p>
					</div>
				</div>
				<div class="flex flex-col md:flex-row items-center gap-8">
					<div class="w-16 h-16 bg-purple-600 rounded-full flex items-center justify-center text-2xl font-bold text-white shrink-0">3</div>
					<div class="flex-1 bg-slate-800/50 rounded-xl p-6 border border-slate-700">
						<h3 class="text-xl font-semibold text-white mb-2">Test Execution</h3>
						<p class="text-gray-400">Running manual and automated tests to identify defects and verify functionality.</p>
					</div>
				</div>
				<div class="flex flex-col md:flex-row items-center gap-8">
					<div class="w-16 h-16 bg-purple-600 rounded-full flex items-center justify-center text-2xl font-bold text-white shrink-0">4</div>
					<div class="flex-1 bg-slate-800/50 rounded-xl p-6 border border-slate-700">
						<h3 class="text-xl font-semibold text-white mb-2">Defect Tracking & Resolution</h3>
						<p class="text-gray-400">Documenting issues, prioritizing fixes, and verifying that solutions work correctly.</p>
					</div>
				</div>
			</div>
		</div>
	</section>

	<!-- Types of Testing Section -->
	<section class="py-20 bg-slate-800/50">
		<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
			<h2 class="text-4xl font-bold text-white text-center mb-16">Types of Testing</h2>
			<div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
				<div class="bg-gradient-to-br from-purple-600 to-purple-800 rounded-xl p-6">
					<h3 class="text-lg font-semibold text-white mb-3">Unit Testing</h3>
					<p class="text-purple-100 text-sm">Testing individual components in isolation to ensure they work as expected.</p>
				</div>
				<div class="bg-gradient-to-br from-blue-600 to-blue-800 rounded-xl p-6">
					<h3 class="text-lg font-semibold text-white mb-3">Integration Testing</h3>
					<p class="text-blue-100 text-sm">Verifying that different modules work together correctly.</p>
				</div>
				<div class="bg-gradient-to-br from-indigo-600 to-indigo-800 rounded-xl p-6">
					<h3 class="text-lg font-semibold text-white mb-3">End-to-End Testing</h3>
					<p class="text-indigo-100 text-sm">Testing complete user workflows from start to finish.</p>
				</div>
				<div class="bg-gradient-to-br from-violet-600 to-violet-800 rounded-xl p-6">
					<h3 class="text-lg font-semibold text-white mb-3">Performance Testing</h3>
					<p class="text-violet-100 text-sm">Ensuring the application performs well under various conditions.</p>
				</div>
				<div class="bg-gradient-to-br from-pink-600 to-pink-800 rounded-xl p-6">
					<h3 class="text-lg font-semibold text-white mb-3">Security Testing</h3>
					<p class="text-pink-100 text-sm">Identifying vulnerabilities and ensuring data protection.</p>
				</div>
				<div class="bg-gradient-to-br from-rose-600 to-rose-800 rounded-xl p-6">
					<h3 class="text-lg font-semibold text-white mb-3">Usability Testing</h3>
					<p class="text-rose-100 text-sm">Evaluating the user experience and interface design.</p>
				</div>
				<div class="bg-gradient-to-br from-fuchsia-600 to-fuchsia-800 rounded-xl p-6">
					<h3 class="text-lg font-semibold text-white mb-3">Regression Testing</h3>
					<p class="text-fuchsia-100 text-sm">Ensuring new changes don't break existing functionality.</p>
				</div>
				<div class="bg-gradient-to-br from-cyan-600 to-cyan-800 rounded-xl p-6">
					<h3 class="text-lg font-semibold text-white mb-3">Accessibility Testing</h3>
					<p class="text-cyan-100 text-sm">Making sure the application is usable by everyone.</p>
				</div>
			</div>
		</div>
	</section>

	<!-- Statistics Section -->
	<section class="py-20">
		<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
			<h2 class="text-4xl font-bold text-white text-center mb-16">The Impact of Quality</h2>
			<div class="grid md:grid-cols-4 gap-8 text-center">
				<div>
					<div class="text-5xl font-bold text-purple-400 mb-2">85%</div>
					<p class="text-gray-400">of users abandon apps due to poor quality</p>
				</div>
				<div>
					<div class="text-5xl font-bold text-purple-400 mb-2">10x</div>
					<p class="text-gray-400">cost increase when bugs reach production</p>
				</div>
				<div>
					<div class="text-5xl font-bold text-purple-400 mb-2">40%</div>
					<p class="text-gray-400">of development time saved with automation</p>
				</div>
				<div>
					<div class="text-5xl font-bold text-purple-400 mb-2">95%</div>
					<p class="text-gray-400">of customers expect flawless experiences</p>
				</div>
			</div>
		</div>
	</section>

	<!-- Best Practices Section -->
	<section class="py-20 bg-slate-800/50">
		<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
			<h2 class="text-4xl font-bold text-white text-center mb-16">QA Best Practices</h2>
			<div class="grid md:grid-cols-2 gap-8">
				<div class="flex gap-4">
					<div class="text-purple-400 text-2xl">✓</div>
					<div>
						<h3 class="text-lg font-semibold text-white mb-2">Shift Left Testing</h3>
						<p class="text-gray-400">Start testing early in the development cycle to catch issues sooner.</p>
					</div>
				</div>
				<div class="flex gap-4">
					<div class="text-purple-400 text-2xl">✓</div>
					<div>
						<h3 class="text-lg font-semibold text-white mb-2">Continuous Integration</h3>
						<p class="text-gray-400">Automate testing as part of your CI/CD pipeline for rapid feedback.</p>
					</div>
				</div>
				<div class="flex gap-4">
					<div class="text-purple-400 text-2xl">✓</div>
					<div>
						<h3 class="text-lg font-semibold text-white mb-2">Test Automation</h3>
						<p class="text-gray-400">Automate repetitive tests to increase coverage and efficiency.</p>
					</div>
				</div>
				<div class="flex gap-4">
					<div class="text-purple-400 text-2xl">✓</div>
					<div>
						<h3 class="text-lg font-semibold text-white mb-2">Cross-functional Collaboration</h3>
						<p class="text-gray-400">Involve developers, testers, and stakeholders throughout the process.</p>
					</div>
				</div>
				<div class="flex gap-4">
					<div class="text-purple-400 text-2xl">✓</div>
					<div>
						<h3 class="text-lg font-semibold text-white mb-2">Risk-based Testing</h3>
						<p class="text-gray-400">Prioritize testing efforts based on business impact and risk.</p>
					</div>
				</div>
				<div class="flex gap-4">
					<div class="text-purple-400 text-2xl">✓</div>
					<div>
						<h3 class="text-lg font-semibold text-white mb-2">Metrics & Reporting</h3>
						<p class="text-gray-400">Track key metrics to measure and improve quality over time.</p>
					</div>
				</div>
			</div>
		</div>
	</section>

	<!-- Footer -->
	<footer class="py-12 border-t border-slate-800">
		<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
			<p class="text-gray-500">Quality is not an act, it is a habit. — Aristotle</p>
			<p class="text-gray-600 mt-4 text-sm">© 2026 Quality Assurance Guide</p>
		</div>
	</footer>
</div>
