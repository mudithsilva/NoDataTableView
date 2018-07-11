# NoDataTableView
TableView Background loader when tableview is empty

#### Step 01

Simply drag and drop ``NoDataTableView`` Folder in you project folder.

#### Step 02

Simply load ``NoDataView`` when the tableView is empty

```
  self.tableView.backgroundView = NoDataView.getNoDataView(iconName: "youIcon", title: "Title for the background View")
  self.tableView.reloadData()

```

if the tableView is not empty, simply add

```
  self.tableView.backgroundView = nil
  self.tableView.reloadData()

```
