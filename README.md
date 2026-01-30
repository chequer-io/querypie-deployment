# QueryPie ACP Helm Chart Repository

**[English]**

[QueryPie Access Control Platform (ACP)](https://docs.querypie.com/) is a unified access control platform for databases, servers, Kubernetes, and web applications.

This repository distributes the QueryPie ACP Helm chart via GitHub Pages.
For installation guide, please refer to [QueryPie Installation Documentation](https://docs.querypie.com/installation).
For questions or support, please visit [QueryPie Community Discussions](https://github.com/querypie/querypie-community/discussions).

You can add the QueryPie Helm repository as follows:

---

**[日本語]**

[QueryPie Access Control Platform (ACP)](https://docs.querypie.com/)は、データベース、サーバー、Kubernetes、Webアプリケーションに対する統合アクセス制御プラットフォームです。

このリポジトリはGitHub Pagesを通じてQueryPie ACP Helmチャートを配布しています。
インストールガイドは[QueryPieインストールドキュメント](https://docs.querypie.com/installation)をご参照ください。
ご質問やサポートについては、[QueryPie Community Discussions](https://github.com/querypie/querypie-community/discussions)をご覧ください。

QueryPie Helmリポジトリは以下のように追加できます：

---

**[한국어]**

[QueryPie Access Control Platform (ACP)](https://docs.querypie.com/)는 데이터베이스, 서버, Kubernetes, 웹 애플리케이션에 대한 통합 접근 제어 플랫폼입니다.

이 레포지토리는 GitHub Pages를 통해 QueryPie ACP Helm 차트를 배포합니다.
설치 가이드는 [QueryPie 설치 문서](https://docs.querypie.com/installation)를 참조해 주세요.
문의 및 지원은 [QueryPie Community Discussions](https://github.com/querypie/querypie-community/discussions)를 이용해 주세요.

QueryPie Helm 레포지토리는 다음과 같이 추가할 수 있습니다:

```bash
$ helm repo add querypie https://chequer-io.github.io/querypie-deployment/helm-chart
"querypie" has been added to your repositories

$ helm repo update
...Successfully got an update from the "querypie" chart repository

$ helm search repo querypie -l
NAME            	CHART VERSION	APP VERSION	DESCRIPTION
querypie/querypie	1.5.0       	11.5.1     	A Helm chart for QueryPie
querypie/querypie	1.4.4       	11.5.0     	A Helm chart for QueryPie
querypie/querypie	1.4.3       	11.3.0     	A Helm chart for QueryPie
querypie/querypie	1.4.2       	11.2.0     	A Helm chart for QueryPie
querypie/querypie	1.4.1       	11.1.0     	A Helm chart for QueryPie
querypie/querypie	1.4.0       	11.0.0     	A Helm chart for QueryPie
...
```

## Helm Chart Source

The Helm chart source code is maintained at https://github.com/chequer-io/querypie-mono/tree/develop/deploy/helm/querypie
