# satplan-pkg
package satplan projects

1. calpath
1.1 git clone
1.2 install sqlite3
1.3 make

2. satplan
2.1 git clone
2.2 go mod download
2.3 go build

3. satplan-web
3.1 git clone
3.2 npm install
3.3 yarn run build

4. docker
4.1 set nginx as base container
4.2 cp calpath, satplan, satplan-web, sat.db
4.3 set data folder
4.4 start satplan as background service
4.5 start nginx
