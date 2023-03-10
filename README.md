''''
import 'package:flutter/material.dart';
import 'package:flutter/src/widgets/framework.dart';
import 'package:flutter/src/widgets/placeholder.dart';
import 'package:get/get.dart';
import 'package:majura/pages/welcome/list.dart';

import '../../components/MyDropDown/MyDropDow.dart';
import '../../config/colors.dart';

class WelcomePage extends StatelessWidget {
  const WelcomePage({super.key});

  @override
  Widget build(BuildContext context) {
    final List<String> options = ['Option 1', 'Option 2', 'Option 3'];
    RadioController radioController = Get.put(RadioController());
    return Scaffold(
        appBar: AppBar(
          title: Text("W E L C O M E"),
          centerTitle: true,
        ),
        body: Column(
          children: [
            AwesomeDropDown(
              dropDownBorderRadius: 0,
              dropDownTopBorderRadius: 10,
              dropDownBottomBorderRadius: 10,
              dropDownList: options,
            )
          ],
        ));
  }
}

''''

![Flutter app ](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEj1UFYlKhl1Inqw0JhPHEATISbAaJElz5UeRMKir8BIrLKBRrHltfgHhhGqo1DnPIaVL78X34DJyBuxSX_YH5s0yx85BCXwLnFnSqROsPiRlKfi3mOL5YGnioaeTMtR-rfz2z7H2o_-iVLHrbf_nDe2QXHbMTQn9GYbIVQoADwXxLJVCNkykGRo4XIXyg/s1200/116820134-420b2400-ab28-11eb-826a-caa69072ba6b.gif)
