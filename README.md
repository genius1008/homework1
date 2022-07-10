东北大学_赵洁_ios开发_作业一

1. 按顺序打印出 App、ViewController 生命周期的各个事件。

  App生命周期：
  
  （1）点击程序图标
  
  （2）执行main函数
  
  （3）通过UIApplicationMain函数
  
  （4）初始化UIApplication对象并且为它设置代理对象
  
  （5）UIApplication对象（监听系统事件）
  
  （6）程序结束退出
    
  ViewController生命周期：
  
  （1）alloc/init
  
  （2）loadView
  
  （3）viewDidLoad
  
  （4）viewWillAppear
  
  （5）viewDidAppear
  
  （6）viewWillDisappear
  
  （7）viewDidDisappear
  
  （8）dealloc

2. 写出五种常用的 UI 控件。

  UIScrollView、UITableView、UICollectionView、UIWebView & WKWebView、UINavigationBar。

3. 列举出三个 UITableViewDelegate 声明的方法。

  （1）选中某行cell调用此方法
    
    (void)tableView:(UITableView *)tableView didSelectRowAtIndexPath:(NSIndexPath *)indexPath;
    
  （2）自定义每组头部的view需要使用到UITableViewHeaderFooterView

    (UIView *)tableView:(UITableView *)tableView viewForHeaderInSection:(NSInteger)section; 

  （3）自定义每组尾部的View需要使用到UITableViewHeaderFooterView

    (UIView *)tableView:(UITableView *)tableView viewForFooterInSection:(NSInteger)section;
