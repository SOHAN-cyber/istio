# Conculsion:
Once you have deployed the query based routing deployment using our manifest. Open the below url in browser

```
curl  http://sohan.com/?user=v1
```
## Output:
![](../images/query-v1.png)

```
curl http://sohan.com/?user=v2
```
## Output:
![](../images/query-v2.png)

```
curl http://sohan.com
```
## Output:
![](../images/default-query.png)

## Kiali DashBoard Output:
![](../images/query-kiali-lab.png)
