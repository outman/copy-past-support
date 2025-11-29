<script>
	import logo from '$lib/assets/logo.png';
	import { base } from '$app/paths';
</script>

<div class="container">
	<!-- Header -->
	<header class="header">
		<div class="logo-container">
			<img src={logo} alt="CopyPast Logo" class="logo" />
		</div>
		<h1 class="title">Privacy Policy</h1>
		<p class="subtitle">隐私政策</p>
	</header>

	<!-- Privacy Content -->
	<section class="privacy-content">
		<!-- Your Privacy Matters to Us -->
		<div class="privacy-section">
			<div class="section-header">
				<div class="section-icon">🔒</div>
				<h2 class="section-title">Your Privacy Matters to Us</h2>
				<p class="section-subtitle">您的隐私对我们很重要</p>
			</div>
			<div class="section-body">
				<p>
					At CopyPast, we are committed to protecting your privacy and ensuring the security of
					your data. We believe that your personal information should remain private and under
					your control.
				</p>
				<p>
					在 CopyPast，我们致力于保护您的隐私并确保您数据的安全。我们相信您的个人信息应该保持私密并在您的控制之下。
				</p>
			</div>
		</div>

		<!-- No Data Collection -->
		<div class="privacy-section">
			<div class="section-header">
				<div class="section-icon">🚫</div>
				<h2 class="section-title">No Data Collection</h2>
				<p class="section-subtitle">不收集数据</p>
			</div>
			<div class="section-body">
				<p>
					CopyPast does not collect, store, or transmit any personal information, user data, or
					device information. All clipboard data is stored locally on your device and never
					leaves your computer.
				</p>
				<p>
					CopyPast 不收集、存储或传输任何个人信息、用户数据或设备信息。所有剪贴板数据都存储在您的设备本地，永远不会离开您的计算机。
				</p>
				<ul class="feature-list">
					<li>No user accounts or registration required / 无需用户账户或注册</li>
					<li>No analytics or tracking / 无分析或跟踪</li>
					<li>No device identifiers collected / 不收集设备标识符</li>
					<li>No location data / 无位置数据</li>
					<li>No network requests for data transmission / 无数据传输的网络请求</li>
				</ul>
			</div>
		</div>

		<!-- No Data Sharing -->
		<div class="privacy-section">
			<div class="section-header">
				<div class="section-icon">🔐</div>
				<h2 class="section-title">No Data Sharing</h2>
				<p class="section-subtitle">不分享数据</p>
			</div>
			<div class="section-body">
				<p>
					Since we do not collect any data, there is nothing to share. Your clipboard history
					remains completely private and is never shared with third parties, advertisers, or
					any external services.
				</p>
				<p>
					由于我们不收集任何数据，因此没有任何内容可以分享。您的剪贴板历史记录完全保持私密，永远不会与第三方、广告商或任何外部服务共享。
				</p>
				<ul class="feature-list">
					<li>No third-party sharing / 不与第三方共享</li>
					<li>No cloud synchronization / 无云同步</li>
					<li>No advertising networks / 无广告网络</li>
					<li>No data brokers / 无数据经纪人</li>
					<li>Complete local control / 完全本地控制</li>
				</ul>
			</div>
		</div>

		<!-- Legal Compliance -->
		<div class="privacy-section">
			<div class="section-header">
				<div class="section-icon">⚖️</div>
				<h2 class="section-title">Legal Compliance</h2>
				<p class="section-subtitle">法律合规</p>
			</div>
			<div class="section-body">
				<p>
					CopyPast is designed to comply with applicable privacy laws and regulations, including
					but not limited to:
				</p>
				<p>
					CopyPast 旨在遵守适用的隐私法律法规，包括但不限于：
				</p>
				<ul class="feature-list">
					<li>General Data Protection Regulation (GDPR) / 通用数据保护条例 (GDPR)</li>
					<li>California Consumer Privacy Act (CCPA) / 加州消费者隐私法 (CCPA)</li>
					<li>Personal Information Protection Law of China / 中华人民共和国个人信息保护法</li>
					<li>Other local and regional privacy regulations / 其他本地和地区隐私法规</li>
				</ul>
				<p>
					By not collecting any personal data, CopyPast inherently respects your privacy rights
					and complies with these regulations.
				</p>
				<p>
					通过不收集任何个人数据，CopyPast 本质上尊重您的隐私权并遵守这些法规。
				</p>
			</div>
		</div>

		<!-- Contact Information -->
		<div class="privacy-section">
			<div class="section-header">
				<div class="section-icon">📧</div>
				<h2 class="section-title">Contact Information</h2>
				<p class="section-subtitle">联系信息</p>
			</div>
			<div class="section-body">
				<p>
					If you have any questions, concerns, or requests regarding this privacy policy or our
					data practices, please contact us:
				</p>
				<p>
					如果您对此隐私政策或我们的数据实践有任何问题、疑虑或请求，请联系我们：
				</p>
				<div class="contact-info">
					<p class="contact-label">Email / 邮箱：</p>
					<p class="contact-value">
						<a href="mailto:pochonlee@gmail.com">pochonlee#gmail.com</a>
					</p>
				</div>
				<p class="last-updated">
					Last Updated / 最后更新: Nov. 2025 / 2025年11月
				</p>
			</div>
		</div>
	</section>

	<!-- Footer -->
	<footer class="footer">
		<p>
			<a href="{base}/" class="back-link">← Back to Home / 返回首页</a>
		</p>
		<p>© 2025 ScrapMind.com All rights reserved.</p>
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
		max-width: 900px;
		margin: 0 auto;
		padding: 2rem 1rem;
	}

	/* Header */
	.header {
		text-align: center;
		padding: 2rem 0 3rem;
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
		font-size: 3rem;
		font-weight: 700;
		margin: 0.5rem 0;
		text-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
	}

	.subtitle {
		font-size: 1.3rem;
		font-weight: 300;
		margin: 0.5rem 0;
		opacity: 0.95;
	}

	/* Privacy Content */
	.privacy-content {
		display: flex;
		flex-direction: column;
		gap: 2rem;
	}

	.privacy-section {
		background: white;
		border-radius: 24px;
		padding: 2.5rem;
		box-shadow: 0 10px 40px rgba(0, 0, 0, 0.1);
		transition: transform 0.3s ease, box-shadow 0.3s ease;
	}

	.privacy-section:hover {
		transform: translateY(-4px);
		box-shadow: 0 15px 50px rgba(0, 0, 0, 0.15);
	}

	.section-header {
		display: flex;
		align-items: center;
		gap: 1rem;
		margin-bottom: 1.5rem;
		padding-bottom: 1.5rem;
		border-bottom: 2px solid #f0f0f0;
	}

	.section-icon {
		font-size: 2.5rem;
		flex-shrink: 0;
	}

	.section-title {
		font-size: 2rem;
		font-weight: 700;
		margin: 0;
		color: #333;
		flex: 1;
	}

	.section-subtitle {
		font-size: 1.1rem;
		font-weight: 400;
		color: #666;
		margin: 0;
	}

	.section-body {
		line-height: 1.8;
		color: #555;
	}

	.section-body p {
		margin: 1rem 0;
		font-size: 1rem;
	}

	.feature-list {
		margin: 1.5rem 0;
		padding-left: 1.5rem;
	}

	.feature-list li {
		margin: 0.75rem 0;
		line-height: 1.6;
	}

	.contact-info {
		background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
		border-radius: 12px;
		padding: 1.5rem;
		margin: 1.5rem 0;
		text-align: center;
	}

	.contact-label {
		font-weight: 600;
		margin: 0.5rem 0;
		color: #333;
	}

	.contact-value {
		margin: 0.5rem 0;
	}

	.contact-value a {
		color: #667eea;
		text-decoration: none;
		font-size: 1.1rem;
		font-weight: 500;
		transition: color 0.3s ease;
	}

	.contact-value a:hover {
		color: #764ba2;
		text-decoration: underline;
	}

	.last-updated {
		margin-top: 2rem;
		padding-top: 1.5rem;
		border-top: 1px solid #e0e0e0;
		font-size: 0.9rem;
		color: #888;
		text-align: center;
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

	.back-link {
		color: white;
		text-decoration: none;
		font-size: 1.1rem;
		opacity: 0.95;
		transition: opacity 0.3s ease;
		display: inline-block;
		margin-bottom: 1rem;
	}

	.back-link:hover {
		opacity: 1;
		text-decoration: underline;
	}

	/* Responsive Design */
	@media (max-width: 768px) {
		.title {
			font-size: 2.2rem;
		}

		.subtitle {
			font-size: 1.1rem;
		}

		.privacy-section {
			padding: 2rem 1.5rem;
		}

		.section-header {
			flex-direction: column;
			align-items: flex-start;
			gap: 0.5rem;
		}

		.section-title {
			font-size: 1.6rem;
		}

		.section-subtitle {
			font-size: 1rem;
		}
	}

	@media (max-width: 640px) {
		.container {
			padding: 1rem;
		}

		.privacy-section {
			padding: 1.5rem 1rem;
		}

		.section-icon {
			font-size: 2rem;
		}

		.section-title {
			font-size: 1.4rem;
		}
	}
</style>

