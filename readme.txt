	
	˵��������Ŀ��ʹ��webpack+ES6����React�������������Hello World�������򵥵���ʽ��

	�������̴������£�

	1��git clone�����أ�

	2��cd init-react ִ��npm install��װ��Ŀ�����������Ҫ�У�

		npm install react react-dom --save-dev
		npm install webpack webpack-dev-server --save-dev
		npm install babel-loader babel-core babel-preset-react babel-preset-es2015 --save-dev

		��Ŀ����Ŀ¼�ṹ��

		--init-react
		  |--app
		  	|--components�����Ŀ¼��
		      		|--Hello�����1��
     			 		|--index.js
      			 		|--index.less
    		     		|--World�����2��
      			 		|--index.js
      			 		|--index.less
    		      		|--index.js������ļ���
  		  |--build�����Ŀ¼��
    			|--index.html
    			|--bundle.js������ļ����� webpack ��������ɵģ�
  		  |--package.json
  		  |--webpack.config.js

	3��package.json��scriptsд���˹�������dev������ǰ�氲װ�õ�webpack-dev-server��������ˢ��ҳ��ʵʱ��ҳ��Ч����ִ������npm run dev��

	   webpack.config.js������Ӧ���ã�
		entry: [
    			'webpack/hot/dev-server',
    			'webpack-dev-server/client?http://localhost:8080',
    			APP_PATH
 		]

	4����װ���������loader:

	   npm install less-loader css-loader style-loader --save-dev

	5���������в��裺

		git clone https://github.com/feishanshan/init-react.git
		cd react-webpack-es6
		npm install
		npm run dev

