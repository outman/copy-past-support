<script>
	import logo from '$lib/assets/logo.png';
	import intro1 from '$lib/assets/intro_1_en.png';
	import intro2 from '$lib/assets/intro_2_en.png';
</script>

<div class="container">
	<!-- Hero Section -->
	<header class="hero">
		<div class="logo-container">
			<img src={logo} alt="CopyPast Logo" class="logo" />
		</div>
		<h1 class="title">CopyPast</h1>
		<p class="subtitle">Your Intelligent Clipboard History Manager</p>
		<p class="description">
			CopyPast is a powerful clipboard management application that helps you keep track of your
			copy history, making it easy to access and reuse your copied content anytime.
		</p>
	</header>

	<!-- Screenshots Section -->
	<section class="screenshots">
		<h2 class="section-title">See CopyPast in Action</h2>
		<div class="screenshot-grid">
			<div class="screenshot-item">
				<img src={intro1} alt="CopyPast Introduction 1" class="screenshot" />
			</div>
			<div class="screenshot-item">
				<img src={intro2} alt="CopyPast Introduction 2" class="screenshot" />
			</div>
		</div>
	</section>

	<!-- Key Features Section -->
	<section class="features">
		<h2 class="section-title">Key Features</h2>
		<div class="features-grid">
			<div class="feature-card">
				<div class="feature-icon">🖥️</div>
				<h3 class="feature-title">Native Application</h3>
				<p class="feature-description">
					Built as a native application for optimal performance and seamless integration with
					your operating system.
				</p>
			</div>
			<div class="feature-card">
				<div class="feature-icon">📦</div>
				<h3 class="feature-title">Small Size</h3>
				<p class="feature-description">
					Lightweight and efficient, CopyPast takes up minimal disk space while delivering
					maximum functionality.
				</p>
			</div>
			<div class="feature-card">
				<div class="feature-icon">⚡</div>
				<h3 class="feature-title">High Performance</h3>
				<p class="feature-description">
					Fast and responsive, CopyPast handles your clipboard history with lightning speed
					and efficiency.
				</p>
			</div>
			<div class="feature-card">
				<div class="feature-icon">💾</div>
				<h3 class="feature-title">Local Storage</h3>
				<p class="feature-description">
					All your clipboard data is stored locally on your device, ensuring quick access
					without internet dependency.
				</p>
			</div>
			<div class="feature-card">
				<div class="feature-icon">🔒</div>
				<h3 class="feature-title">Secure & Private</h3>
				<p class="feature-description">
					Your clipboard history remains private and secure, with no cloud sync or external
					data sharing.
				</p>
			</div>
		</div>
	</section>

	<!-- Functionality Section -->
	<section class="functionality">
		<h2 class="section-title">Functionality</h2>
		<div class="functionality-list">
			<div class="functionality-item">
				<div class="functionality-icon">🎨</div>
				<div class="functionality-content">
					<h3 class="functionality-title">Double-click title to change background</h3>
					<p class="functionality-description">
						Customize your view instantly by double-clicking the title bar. Personalize
						CopyPast to match your style and preferences.
					</p>
				</div>
			</div>
			<div class="functionality-item">
				<div class="functionality-icon">📋</div>
				<div class="functionality-content">
					<h3 class="functionality-title">Multi-format Support</h3>
					<p class="functionality-description">
						Compatible with text, images, and files. CopyPast handles all types of content
						you copy, making it versatile for any workflow.
					</p>
				</div>
			</div>
			<div class="functionality-item">
				<div class="functionality-icon">📝</div>
				<div class="functionality-content">
					<h3 class="functionality-title">Add Notes</h3>
					<p class="functionality-description">
						Annotate your clipboard history easily. Add notes to your copied items to
						remember context and organize your content better.
					</p>
				</div>
			</div>
		</div>
	</section>

	<!-- Footer -->
	<footer class="footer">
		<p>© 2025 ScrapMind.com All rights reserved.</p>
		<div class="contact-email">
			<p>联系我们 / Contact Us:</p>
			<p>
				<a href="mailto:pochonlee@gmail.com">pochonlee#gmail.com</a>
			</p>
		</div>
	</footer>
</div>

<style>
	:global(body) {
		margin: 0;
		padding: 0;
		font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial,
			sans-serif;
		background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
		min-height: 100vh;
		color: #333;
	}

	.container {
		max-width: 1200px;
		margin: 0 auto;
		padding: 2rem 1rem;
	}

	/* Hero Section */
	.hero {
		text-align: center;
		padding: 3rem 0;
		color: white;
	}

	.logo-container {
		margin-bottom: 1.5rem;
	}

	.logo {
		width: 80px;
		height: 80px;
		border-radius: 16px;
		background: white;
		padding: 8px;
		box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
	}

	.title {
		font-size: 3.5rem;
		font-weight: 700;
		margin: 0.5rem 0;
		text-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
	}

	.subtitle {
		font-size: 1.5rem;
		font-weight: 300;
		margin: 0.5rem 0 1rem;
		opacity: 0.95;
	}

	.description {
		font-size: 1.1rem;
		max-width: 600px;
		margin: 1.5rem auto;
		opacity: 0.9;
		line-height: 1.6;
	}

	/* Screenshots Section */
	.screenshots {
		background: white;
		border-radius: 24px;
		padding: 3rem 2rem;
		margin: 3rem 0;
		box-shadow: 0 10px 40px rgba(0, 0, 0, 0.1);
	}

	.section-title {
		font-size: 2.5rem;
		font-weight: 700;
		text-align: center;
		margin-bottom: 2.5rem;
		color: #333;
	}

	.screenshot-grid {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
		gap: 2rem;
		margin-top: 2rem;
	}

	.screenshot-item {
		border-radius: 12px;
		overflow: hidden;
		box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
		transition: transform 0.3s ease, box-shadow 0.3s ease;
	}

	.screenshot-item:hover {
		transform: translateY(-4px);
		box-shadow: 0 8px 30px rgba(0, 0, 0, 0.15);
	}

	.screenshot {
		width: 100%;
		height: auto;
		display: block;
	}

	/* Features Section */
	.features {
		background: white;
		border-radius: 24px;
		padding: 3rem 2rem;
		margin: 3rem 0;
		box-shadow: 0 10px 40px rgba(0, 0, 0, 0.1);
	}

	.features-grid {
		display: grid;
		grid-template-columns: repeat(5, 1fr);
		gap: 1.5rem;
		margin-top: 2rem;
	}

	.feature-card {
		background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
		border-radius: 16px;
		padding: 1.5rem;
		text-align: center;
		transition: transform 0.3s ease, box-shadow 0.3s ease;
	}

	.feature-card:hover {
		transform: translateY(-8px);
		box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
	}

	.feature-icon {
		font-size: 2.5rem;
		margin-bottom: 0.75rem;
	}

	.feature-title {
		font-size: 1.2rem;
		font-weight: 600;
		margin: 0.5rem 0;
		color: #333;
	}

	.feature-description {
		font-size: 0.9rem;
		line-height: 1.5;
		color: #555;
		margin: 0;
	}

	/* Functionality Section */
	.functionality {
		background: white;
		border-radius: 24px;
		padding: 3rem 2rem;
		margin: 3rem 0;
		box-shadow: 0 10px 40px rgba(0, 0, 0, 0.1);
	}

	.functionality-list {
		display: flex;
		flex-direction: column;
		gap: 2rem;
		margin-top: 2rem;
	}

	.functionality-item {
		display: flex;
		align-items: flex-start;
		gap: 1.5rem;
		background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
		border-radius: 16px;
		padding: 2rem;
		transition: transform 0.3s ease, box-shadow 0.3s ease;
	}

	.functionality-item:hover {
		transform: translateX(8px);
		box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
	}

	.functionality-icon {
		font-size: 3rem;
		flex-shrink: 0;
	}

	.functionality-content {
		flex: 1;
	}

	.functionality-title {
		font-size: 1.5rem;
		font-weight: 600;
		margin: 0 0 0.5rem;
		color: #333;
	}

	.functionality-description {
		font-size: 1rem;
		line-height: 1.6;
		color: #555;
		margin: 0;
	}

	/* Footer */
	.footer {
		text-align: center;
		padding: 2rem 0;
		color: white;
		opacity: 0.9;
	}

	.footer p {
		margin: 0.5rem 0;
	}

	.contact-email {
		margin-top: 1rem;
		font-size: 1.1rem;
	}

	.contact-email a {
		color: white;
		text-decoration: none;
		opacity: 0.95;
		transition: opacity 0.3s ease;
	}

	.contact-email a:hover {
		opacity: 1;
		text-decoration: underline;
	}

	/* Responsive Design */
	@media (max-width: 1024px) {
		.features-grid {
			grid-template-columns: repeat(3, 1fr);
		}
	}

	@media (max-width: 768px) {
		.title {
			font-size: 2.5rem;
		}

		.subtitle {
			font-size: 1.2rem;
		}

		.screenshot-grid {
			grid-template-columns: 1fr;
		}

		.features-grid {
			grid-template-columns: repeat(2, 1fr);
		}

		.feature-card {
			padding: 1.5rem;
		}

		.feature-title {
			font-size: 1.2rem;
		}

		.feature-description {
			font-size: 0.9rem;
		}
	}

	@media (max-width: 640px) {
		.features-grid {
			grid-template-columns: 1fr;
		}

		.functionality-item {
			flex-direction: column;
			text-align: center;
		}

		.container {
			padding: 1rem;
		}

		.screenshots,
		.features,
		.functionality {
			padding: 2rem 1.5rem;
		}
	}
</style>
