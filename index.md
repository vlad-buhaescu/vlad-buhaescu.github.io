---
layout: page
title: Hello World!
subtitle: 
overridetitle: true
---

### Hello world
```
class ViewController: UIViewController {
    
    @IBOutlet weak var displayLabel: UILabel!
    
    @IBAction func saySomethingTapped(sender: UIButton) {
        displayLabel.text = "Hello World!"
    }
    
    override func viewDidLoad() {
        super.viewDidLoad()
        // Do any additional setup after loading the view, typically from a nib.
    }
 
    override func didReceiveMemoryWarning() {
        super.didReceiveMemoryWarning()
        // Dispose of any resources that can be recreated.
    }
 
}
```
