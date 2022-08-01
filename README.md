``` ts
const name: string = 'Philipp Kremer';
let age: string = new Date().getFullYear() - 2001
const privateProjects: string = 'github.com/pacz-dev';

class About extends Me {
    function getCurrentWorkplace() {
        return {
            company: 'Ionos SE',
            position: 'Software Developer'
        }
    }
    
    function getKnowledge() {
        return {
            [
                'javascript',
                'typescript',
                'vue.js',
                'react',
                'xamarin.forms',
                'flutter',
                'dotNet',
                'java',
                'sql',
                'postgresql',
                'azure'
            ]
        }
    }
}
```