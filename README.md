# Netflix clone を作ろうの Youtube を見て。 Next.js + Tailwind CSS Example
参考. Building a Netflix Clone with Next.js, Tailwind CSS, and Next Auth 

# Next-auth に Firebase を利用
Firebase authenticationの Sign-in method でGoogle認証を選んで、それのウェブSDK構成、
- ウェブ クライアントID
- ウェブ クライアント シークレット
を [...nextauth].jsに利用

## リダイレクトでエラー
GCPのAPI&ServiceのCredentialsの OAuth2.0 Client IDs のところで、リダイレクト先を追加。ローカルで動かすならこんな感じ。
- http://localhost:3000/api/auth/callback/google


# learn-nextjs-tailwind-nextauth
