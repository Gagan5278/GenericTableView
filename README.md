# GenericTableView
An example to use of generics with UITableViewController. With help of GenericListViewController.swift and BaseTableViewCell.swift, data can be populated without worrying about cell registration and TableView DataSource methods.

## HOW TO USE
 - Drag- Drop 'GenericListViewController.swift' and 'BaseTableViewCell.swift' file into your project folder.
  - Create your data model say ModelRoot.
 - Create a subclass of GenericListViewController say RootViewController.
 - Create subclass of BaseTableViewCell say RootTableViewCell.
 
 ####  Your custom cell code will be as below
  ```
    class RootTableViewCell: BaseTableViewCell<ModelRoot> {
          fileprivate let padding_constant: CGFloat = 10.0
         //Just to customize table cell and to explain use of custom cell
         var labelName: UILabel!
    }
    
    ```

  
 
