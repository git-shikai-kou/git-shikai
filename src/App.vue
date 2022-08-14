<template>
  <div>
    <h1>Git・GitHubの発展</h1>

    <h2>チーム開発の流れ</h2>

    <h1>たかひろ参上！！！！</h1>

    <h3>
      1.リモートリポジトリの状態をローカルリポジトリのmasterブランチに取り入れ、最新の状態にする
    </h3>
    <ol>
      <li>git checkout master</li>
      <li>git fetch</li>
      <li>git merge origin/master</li>
    </ol>
    <h3>2.ブランチを切って開発をする</h3>
    <ol>
      <li>git branchでブランチを作成</li>
      <li>git checkout ブランチ名 <br />開発し終えたら...</li>
      <li>git commit -m "コミットメッセージ"</li>
      <li>git push origin ブランチ名</li>
    </ol>
    <h3>3.Pull requestを作成する</h3>
    <ol>
      <li>GitHub で、Compare & pull requestをクリック</li>
      <li>必要事項を記入し、Create pull request</li>
    </ol>
    <h3>4.開発した人以外の人がレビューしてマージする</h3>
    <ol>
      <li>
        Pull requestをレビューし、問題なかったらMerge pull requestでマージする
      </li>
    </ol>
    <h4>これを繰り返す！</h4>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
