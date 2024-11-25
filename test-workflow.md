<p><a target="_blank" href="https://app.eraser.io/workspace/YfvBYufitpYt9XgOQCv8" id="edit-in-eraser-github-link"><img alt="Edit in Eraser" src="https://firebasestorage.googleapis.com/v0/b/second-petal-295822.appspot.com/o/images%2Fgithub%2FOpen%20in%20Eraser.svg?alt=media&amp;token=968381c8-a7e7-472a-8ed6-4a6626da5501"></a></p>

- Investigate batching aisle/aisle_column inserts together to reduce number of SQL invocations
- Investigate performance on planogram inserts
- Remove `change_trigger_column()`  Trigger on the `bin`  table - measure TJs map upload with and without it
- Measure performance by bypassing the search index inserts - test by overwriting entity methods
- Reduce the size of the DB connection pool to see if reduce lock contention - re: LW lock due to contention on same tables



<!-- eraser-additional-content -->
## Diagrams
<!-- eraser-additional-files -->
<a href="/test-workflow-Database Performance Investigation-1.eraserdiagram" data-element-id="JlmdMPzYh0plSFXxidgng"><img src="/.eraser/YfvBYufitpYt9XgOQCv8___mKy49QBroXMQjm1CVOFTAwGSS4q2___---diagram----99ed1e6e9947e082c28e666e524df803-Database-Performance-Investigation.png" alt="" data-element-id="JlmdMPzYh0plSFXxidgng" /></a>
<!-- end-eraser-additional-files -->
<!-- end-eraser-additional-content -->
<!--- Eraser file: https://app.eraser.io/workspace/YfvBYufitpYt9XgOQCv8 --->