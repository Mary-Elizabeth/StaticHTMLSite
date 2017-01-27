<!DOCTYPE html>
<html lang="en">

<head>
	<title>Cheat Sheet CS-2610</title>
	<!-- BootStrap needed HTML -->
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
	
	<!-- Style HTML, instead of CSS StyleSheet -->
	<style>
		/* Header and Footer Styles */	
		header {
			background-color: #555;
			color: white;
			padding: 15px;
		}
		
		footer {
			background-color: #555;
			color: white;
			padding: 15px;
			box-shadow: 0px 9999px 0px 9999px #555;
		}
		
		/* Main Body Styles */
		.panel-body {
			margin: auto;
			width: 80%;
			background-color: #fff;
			border-left: 3px solid #666;
			border-right: 3px solid #666;
			padding: 10px;
		}
		
		body {
			background-color: #f1f1f1;
		}
		
		/* Table Styles */
		.td-mono {
			font-family: monospace;
			font-size: 13px;
			font-style: normal;
			font-variant: normal;
			font-weight: 400;
			line-height: 18.5714px;
		}
		
		td {
			padding: 8px;
			line-height: 1.42857143;
			vertical-align: top;
			border-top: 1px solid #ddd;
		}
		

		/*	Link Styles */	
		a:link {
			color: white;
		}
		
		a:visited {
			color: #80e5ff;
		}
		
		a:hover {
			color: #f2f2f2;
		}
	</style>
</head>

<body><span style="color:#404040;">
	<header class="container-fluid text-center">
		<div class="row">
			<div class="col-xs-12 hidden-sm hidden-md hidden-lg">
				<img src="html-static-site.png" alt="Banner Image" height="85" width="500">
				<!--Mobile-->
			</div>
			<div class="hidden-xs col-sm-12 hidden-md hidden-lg">
				<img src="html-static-site.png" alt="Banner Image" height="120" width="800">
				<!--Tab-->
			</div>
			<div class="hidden-xs hidden-sm col-md-12 hidden-lg">
				<img src="html-static-site.png" alt="Banner Image" height="150" width="1000">
				<!--Desktop-->
			</div>
			<div class="hidden-xs hidden-sm hidden-md col-lg-12">
				<img src="html-static-site.png" alt="Banner Image" height="170" width="1200">
				<!--Large-->
			</div>
		</div>
	</header>

	<div class="panel-body">
		<div class="container-fluid">
			<div class="row">

				<h1>Assignment Overview</h1>
				<p>Establish your online presence with a simple web page written in HTML5. On this site you will create a Unix shell command cheat sheet where you will note:</p>
<ul>
  <li>Unix shell command name</li>
  <li>Description of command</li>
  <li>Example usage</li>
</ul>
<br>
<p>At minimum your page should make use of the following HTML5 tags:</p>
<ul>
  <li>&lt;title&gt;</li>
  <li>&lt;p&gt;</li>
  <li>&lt;span&gt;</li>
  <li>&lt;h1&gt;</li>
  <li>&lt;h2&gt;</li>
  <li>&lt;table&gt;</li>
  <li>&lt;th&gt;</li>
  <li>&lt;tr&gt;</li>
	<li>&lt;td&gt;</li>
	<li>&lt;a&gt;</li>
	<li>&lt;img&gt;</li>
</ul>
<br>
<p>Bonus points will be awarded if you display the example usage in a <span style="font-family: monospace;">monospace</span> font</p>
	<hr>
	<h2><img src="unix-logo.png" alt="Unix Logo" height="30" width="30" style="margin:0px 5px 5px">Unix Shell Commands</h2>
	<p>A list of basic unix shell commands and an example of implementation...</p>
	<div class="panel panel-default">
		<div class="panel-heading">Unix Shell Commands</div>
		<table class="table">
			<tr>
				<th>Command</th>
				<th>Description</th>
				<th>Example</th>
			</tr>
			<tr>
				<td class="td-mono">cat</td>
				<td>outputs the contents of a text file</td>
				<td class="td-mono">
					<p>$ cat file1 >> file2</p>
					<p>$ cat myfile</p>
				</td>
			</tr>
			<tr>
				<td class="td-mono">cd</td>
				<td>changes your current directory location</td>
				<td class="td-mono">
					<p>$ cd myfiles</p>
					<p>$ cd /home/dvader/empire_docs</p>
				</td>
			</tr>
			<tr>
				<td class="td-mono">cp</td>
				<td>copies a file, preserving the original and creating an identical copy</td>
				<td class="td-mono">
					<p>$ cp -i oldfile newfile</p>
					<p>$ cp -i oldfile ~/mystuff/newfile</p>
				</td>
			</tr>
			<tr>
				<td class="td-mono">df / du </td>
				<td>reports disk usage (df:system file) </td>
				<td class="td-mono">
					<p>$ du</p>
					<p>$ df</p>
					<p>$ df -k</p>
				</td>
			</tr>
			<tr>
				<td class="td-mono">find</td>
				<td>lists all of the files within a directory and its subdirectories that match a set of conditions</td>
				<td class="td-mono">
					<p>$ find . -name myfile.txt -print </p>
					<p>$ find . -name "*.txt" -print</p>
				</td>
			</tr>
			<tr>
				<td class="td-mono">jobs  or % [job number]</td>
				<td>reports any programs that you suspended and still have running or waiting in the background</td>
				<td class="td-mono">
					<p>$ jobs </p>
					<p>$ %2</p>
				</td>
			</tr>
						<tr>
				<td class="td-mono">kill</td>
				<td>last resort to destroy any jobs or programs that you suspended and are unable to restart</td>
				<td class="td-mono">
					<p>$ kill %3</p>
					<p>$ kill -9 %3</p>
				</td>
			</tr>
			<tr>
				<td class="td-mono">ls [options] [filename ...]</td>
				<td>list files</td>
				<td class="td-mono">
					<p>$ ls</p>
					<p>hello-world.html</p>
				</td>
			</tr>
			<tr>
				<td class="td-mono">man [command] or [-k keyword]</td>
				<td>displays the manual page for a particular command</td>
				<td class="td-mono">
					<p>$ man ls/p>
					<p>$ man -k keyword </p>
				</td>
			</tr>
			<tr>
				<td class="td-mono">mkdir [-p] path</td>
				<td>
					<p>create a new directory under your PWD</p>
					<p>With -p, create a new directory tree </p>
				</td>
				<td class="td-mono">
					<p>$ mkdir mystuff </p>
					<p>$ mkdir /tmp/morestuff </p>
				</td>
			</tr>
			<tr>
				<td class="td-mono">mv -i [filename....] [directory ...]</td>
				<td>$ move a file</td>
				<td>$ mv -i newhw/hw1 oldhw/firsthw </td>
			</tr>
			<tr>
				<td class="td-mono">ps [options] [PID ...]</td>
				<td>list processes</td>
				<td>
					<p>$ ps -elf</p>
					<p>$ ps -alxww</p>
					</td>
			</tr>
						<tr>
				<td class="td-mono">pwd</td>
				<td>reports the current directory path</td>
				<td>
					<p>$ pwd</p>
					</td>
			</tr>
			<tr>
				<td class="td-mono">rm [options] [filename ...]</td>
				<td>remove (destroy) a file</td>
				<td>
					<p>$ rm -i junk</p>
					<p>$ rm -rf oldstuff</p>
					</td>
			</tr>
			<tr>
				<td class="td-mono">rmdir [subdirectory ...]</td>
				<td>remove a subdirectory</td>
				<td>
					<p>$ rmdir oldstuff </p>
					</td>
			</tr>
		</table>
	</div>

	<hr>
	<h2><img src="git-logo.png" alt="Git Logo" height="30" width="30" style="margin:0px 5px 5px">Git Commands</h2>
	<p>A list of basic git commands and an example of implementation...</p>
	<div class="panel panel-default">
		<div class="panel-heading">Git Commands</div>
		<table class="table">
			<tr>
				<th>Command</th>
				<th>Description</th>
				<th>Example</th>
			</tr>
			<tr>
				<td class="td-mono">git add [filename...]</td>
				<td>add one or more files to staging (index)</td>
				<td class="td-mono">
					<p>git add myfile</p>
					<p>git add *</p>
				</td>
			</tr>
			<tr>
				<td class="td-mono">git commit [option] [commit message...]</td>
				<td>commit changes to head (but not yet to the remote repository)</td>
				<td class="td-mono">
					<p>git commit -m "Commit message"</p>
				</td>
			</tr>
			<tr>
				<td class="td-mono">git push [branch name...]</td>
				<td>send changes to the master branch of your remote repository</td>
				<td class="td-mono">
					<p>git push origin master</p>
				</td>
			</tr>
			<tr>
				<td class="td-mono">git status</td>
				<td>list the files you've changed and those you still need to add or commit</td>
				<td class="td-mono">
					<p>git status</p>
				</td>
			</tr>
						<tr>
				<td class="td-mono">git checkout [option -b] [branchname...]</td>
				<td>create a new branch and switch to it</td>
				<td class="td-mono">
					<p>git checkout -b branch</p>
				</td>
			</tr>
		</table>
	</div>
	<hr>
	<h2><img src="html-logo.png" alt="HTML logo" height="30" width="30" style="margin:0px 5px 5px">HTML Tags & Attributes</h2>
	<p>A list of basic HTML tags and their attributes...</p>
	<div class="panel panel-default">
		<!-- Default panel contents -->
		<div class="panel-heading">HTML Tags</div>
		<table class="table">
			<tr>
				<th>Tag</th>
				<th>Attributes</th>
				<th>Description</th>
				<th>Example</th>
			</tr>
			<tr>
				<td class="td-mono">&lt;!DOCTYPE&gt;</td>
				<td>n/a</td>
				<td>defines the document type</td>
				<td class="td-mono">&lt;!DOCTYPE html&gt;&lt;/html&gt;</td>
			</tr>
			<tr>
				<td class="td-mono">&lt;title&gt;</td>
				<td>n/a</td>
				<td>defines a title for the document</td>
				<td class="td-mono">&lt;title&gt;Example Title&lt;/title&gt;</td>
			</tr>
			<tr>
				<td class="td-mono">&lt;body&gt;</td>
				<td>supports global and event attributes</td>
				<td>defines the document's body</td>
				<td class="td-mono">&lt;body&gt;&lt;/body&gt;</td>
			</tr>
						<tr>
				<td class="td-mono">&lt;h1&gt; to &lt;h6&gt;</td>
				<td>align, supports global and event attributes</td>
				<td>defines the document's body</td>
				<td class="td-mono">&lt;h3&gt;Heading #3&lt;/h3&gt;</td>
			</tr>
						<tr>
				<td class="td-mono">&lt;p&gt;</td>
				<td>align, supports global and event attributes</td>
				<td>defines a paragraph</td>
				<td class="td-mono">&lt;p&gt;This is text that belongs in a paragraph&lt;/p&gt;</td>
			</tr>
						<tr>
				<td class="td-mono">&lt;!--...--&gt;</td>
				<td>n/a</td>
				<td>defines a comment</td>
				<td class="td-mono">&lt;!--&gt;comments are inserted here&lt;--&gt;</td>
			</tr>
						<tr>
				<td class="td-mono">&lt;img&gt;</td>
				<td>supports global attributes</td>
				<td>defines an image</td>
				<td class="td-mono">&lt;img src="unix-logo.png" alt="Unix Logo"&gt;</td>
			</tr>
		</table>
		<br>
	</div>
	</div>
	</div>
	</div>

	<footer class="container-fluid text-center">
		<h4>References</h4>
		<p>
			<a href="https://www.tjhsst.edu/~dhyatt/superap/unixcmd.html">UNIX SHELL COMMANDS</a> |
			<a href="https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html">GIT COMMANDS</a> |
			<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element">HTML ELEMENTS</a>
		</p>
		<p>2017 - Mary Dettenmaier - CS2610 - Assignment #4</p>
	</footer>
	</span>
</body>

</html>

