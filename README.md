<h1><span>使用終端機註冊macOS Beta Seed</span></h1>
<h2><a id="user-content-usage" class="anchor" href="https://gist.github.com/pookjw/b17da769e9c3b061f9a5bcf3f7990866#usage" aria-hidden="true"></a><span>用法</span></h2>
<pre><code>$ sudo /System/Library/PrivateFrameworks/Seeding.framework/Versions/A/Resources/seedutil 
usage: seedutil enroll SEED_PROGRAM
    seedutil unenroll
    seedutil current
    seedutil migrate OLD_VERSION NEW_VERSION
    seedutil fixup
</code></pre>
<h2><a id="user-content-enroll-developerseed-developer-beta" class="anchor" href="https://gist.github.com/pookjw/b17da769e9c3b061f9a5bcf3f7990866#enroll-developerseed-developer-beta" aria-hidden="true"></a><span>註冊DeveloperSeed（開發人員Beta）</span></h2>
<p><code>sudo /System/Library/PrivateFrameworks/Seeding.framework/Versions/A/Resources/seedutil enroll DeveloperSeed</code></p>
<h2><a id="user-content-enroll-publicseed-public-beta" class="anchor" href="https://gist.github.com/pookjw/b17da769e9c3b061f9a5bcf3f7990866#enroll-publicseed-public-beta" aria-hidden="true"></a><span>註冊PublicSeed（公開Beta版）</span></h2>
<p><code>sudo /System/Library/PrivateFrameworks/Seeding.framework/Versions/A/Resources/seedutil enroll PublicSeed</code></p>
<h2><a id="user-content-unenroll-seed" class="anchor" href="https://gist.github.com/pookjw/b17da769e9c3b061f9a5bcf3f7990866#unenroll-seed" aria-hidden="true"></a><span>取消註冊</span></h2>
<p><code>sudo /System/Library/PrivateFrameworks/Seeding.framework/Versions/A/Resources/seedutil unenroll</code></p>
<h2><a id="user-content-see-enrolled-seed" class="anchor" href="https://gist.github.com/pookjw/b17da769e9c3b061f9a5bcf3f7990866#see-enrolled-seed" aria-hidden="true"></a><span>查看已註冊狀態</span></h2>
<p><code>sudo /System/Library/PrivateFrameworks/Seeding.framework/Versions/A/Resources/seedutil current</code></p>
