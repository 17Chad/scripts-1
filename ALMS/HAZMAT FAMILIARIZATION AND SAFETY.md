<pre><code>test=document.frames(1).frames(1).frames(1).parent.API_1484_11;
test.dataModelInterface.root.containers.cmi.elements.scaled_passing_score.writeable=true;

test.SetValue("cmi.scaled_passing_score", 0.8);
test.SetValue("cmi.score.scaled", 0.9);
test.SetValue("cmi.completion_status", "completed");
test.SetValue("cmi.success_status", "passed");
test.SetValue("cmi.score.raw", 90);
test.SetValue("adl.nav.request", "continue");

test.completeUserSession(true);</code></pre>
