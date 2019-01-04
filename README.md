# PullMenuView
类型微信右上角的下拉框

ZWPullMenuView *menuView = [ZWPullMenuView pullMenuAnchorPoint:CGPointMake(self.view.width-20, kStatusBarHeight + 44) titleArray:titleArr imageArray:@[@"inform"]];
        menuView.zwPullMenuStyle = PullMenuDarkStyle;
        typeof (self) __weak weakSelf = self;
        menuView.blockSelectedMenu = ^(NSInteger menuRow) {
            
        };
