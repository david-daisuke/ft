# P2P File Transfer

A simple tool for P2P file transfer in browser using TypeScript, React.js and Peer.js
下記のファイル転送ソフトのソースのcloneです
See at: [https://chidokun.github.io/p2p-file-transfer](https://chidokun.github.io/p2p-file-transfer)


appspec.yml　　　　　アプリをインストールするステップ
buildspec.yml　　　　ビルドに必要なステップ

ECRでp2p-file-transfer　がレポジトリとして登録されてないと失敗します

環境変数はcode build にいれておきました

ポリシーは下記の通り
AmazonEC2ContainerRegistryFullAccess
AmazonEC2ContainerRegistryPowerUser
AmazonEC2RoleforSSM
AmazonS3FullAccess
AWSCodeDeployRole
AWSCodeDeployRoleForECS
AWSCodePipeline_FullAccess
CodeBuildBasePolicy-codedeployftforubuntu2-us-east-1
