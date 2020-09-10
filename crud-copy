from PyQt5 import QtCore, QtGui, QtWidgets


class Ui_Form(object):
    def setupUi(self, Form):
        Form.setObjectName("Form")
        Form.resize(204, 172)
        Form.setCursor(QtGui.QCursor(QtCore.Qt.ArrowCursor))
        self.Copy = QtWidgets.QPushButton(Form)
        self.Copy.setGeometry(QtCore.QRect(60, 50, 75, 23))
        self.Copy.setObjectName("Copy")
        self.Vvod = QtWidgets.QTextEdit(Form)
        self.Vvod.setGeometry(QtCore.QRect(20, 10, 161, 31))
        self.Vvod.setObjectName("Vvod")
        self.Vivod = QtWidgets.QTextBrowser(Form)
        self.Vivod.setGeometry(QtCore.QRect(20, 80, 161, 81))
        self.Vivod.setContextMenuPolicy(QtCore.Qt.ActionsContextMenu)
        self.Vivod.setLocale(QtCore.QLocale(QtCore.QLocale.Russian, QtCore.QLocale.Russia))
        self.Vivod.setObjectName("Vivod")

        self.retranslateUi(Form)
        QtCore.QMetaObject.connectSlotsByName(Form)

    def retranslateUi(self, Form):
        _translate = QtCore.QCoreApplication.translate
        Form.setWindowTitle(_translate("Form", "Copyper"))
        self.Copy.setText(_translate("Form", "Copy"))

if __name__ == "__main__":
  import sys
  app = QtWidgets.QApplication(sys.argv)
  Form = QtWidgets.QWidget()
  ui = Ui_Form()
  ui.setupUi(Form)
  Form.show()
  sys.exit(app.exec_())
