## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/978420544/wxcc/edit/gh-pages/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
import org.quartz.JobExecutionContext;  
import org.quartz.JobExecutionException;  
import org.springframework.scheduling.quartz.QuartzJobBean;  
public class Job1 extends QuartzJobBean {  
  
private int timeout;  
private static int i = 0;  
//调度工厂实例化后，经过timeout时间开始执行调度  
public void setTimeout(int timeout) {  
this.timeout = timeout;  
}  
  
/** 
* 要调度的具体任务 
*/  
@Override  
protected void executeInternal(JobExecutionContext context)  
throws JobExecutionException {  
  System.out.println("定时任务执行中…");  
}  
}
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/978420544/wxcc/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
