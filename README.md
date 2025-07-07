# QueryPie Deployment

안녕하세요. QueryPie Helm 차트를 관리하는 레포지토리 입니다.

이 페이지는 github page 를 통해 배포된 문서입니다.

QueryPie helm 차트는 다음과 같이 사용할 수 있습니다.

```bash
$ helm repo add querypie https://chequer-io.github.io/querypie-deployment/helm-chart
"querypie" has been added to your repositories

$ helm repo list
NAME                       	URL    
querypie                   	https://chequer-io.github.io/querypie-deployment/helm-chart

$ helm search repo querypie -l
NAME            	CHART VERSION	APP VERSION	DESCRIPTION
querypie/querypie	1.4.0       	11.0.0     	A Helm chart for QueryPie
querypie/querypie	1.3.9        	10.3.0     	A Helm chart for QueryPie
querypie/querypie	1.3.8        	10.2.8     	A Helm chart for QueryPie
querypie/querypie	1.3.7        	10.2.2     	A Helm chart for QueryPie
querypie/querypie	1.3.6        	10.2.2     	A Helm chart for QueryPie
querypie/querypie	1.3.5        	10.2.2     	A Helm chart for QueryPie
querypie/querypie	1.3.4        	10.2.1     	A Helm chart for QueryPie
querypie/querypie	1.3.3        	10.2.0     	A Helm chart for QueryPie
querypie/querypie	1.3.1        	10.1.0     	A Helm chart for QueryPie (add rdp pvc) 
querypie/querypie	1.3.0        	10.1.0     	A Helm chart for QueryPie
querypie/querypie	1.2.1        	9.20.0     	A Helm chart for QueryPie
querypie/querypie	1.2.0        	9.20.0     	A Helm chart for QueryPie
querypie/querypie	1.1.0        	9.18.0     	A Helm chart for QueryPie
querypie/querypie	1.0.0        	9.17.0     	A Helm chart for QueryPie
```

자세한 사항은 https://www.querypie.com/contacts 를 통해 문의해 주세요.

## Helm Chart

helm 차트 코드는 https://github.com/chequer-io/querypie-mono/tree/develop/deploy/helm/querypie 에서 관리되고 있습니다.

