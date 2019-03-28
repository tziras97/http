const opts = {
  root: path.join(__dirname, 'public'),
  baseDir: '/',
  autoIndex: true,
});

http.createServer(ecstatic).listen(8080);

console.log('Listening on :8080');