from PySide2.QtCore import (QCoreApplication, QMetaObject, QObject, QPoint,
                            QRect, QSize, QUrl, Qt)
from PySide2.QtGui import (QBrush, QColor, QConicalGradient, QCursor, QFont,
                           QFontDatabase, QIcon, QLinearGradient, QPalette, QPainter, QPixmap,
                           QRadialGradient)
from PySide2.QtWidgets import *
 
 
class Ui_MainWindow(object):
    def setupUi(self, MainWindow):
        if MainWindow.objectName():
            MainWindow.setObjectName(u"MainWindow")
        MainWindow.resize(372, 645)
        self.centralwidget = QWidget(MainWindow)
        self.centralwidget.setObjectName(u"centralwidget")
        self.verticalLayout = QVBoxLayout(self.centralwidget)
        self.verticalLayout.setObjectName(u"verticalLayout")
        self.message_box = QPlainTextEdit(self.centralwidget)
        self.message_box.setObjectName(u"message_box")
        self.message_box.setReadOnly(True)
 
        self.verticalLayout.addWidget(self.message_box)
 
        self.message_input = QLineEdit(self.centralwidget)
        self.message_input.setObjectName(u"message_input")
 
        self.verticalLayout.addWidget(self.message_input)
 
        self.message_button = QPushButton(self.centralwidget)
        self.message_button.setObjectName(u"message_button")
 
        self.verticalLayout.addWidget(self.message_button)
 
        MainWindow.setCentralWidget(self.centralwidget)
 
        self.retranslateUi(MainWindow)
 
        QMetaObject.connectSlotsByName(MainWindow)
 
 
 
    def retranslateUi(self, MainWindow):
        MainWindow.setWindowTitle(QCoreApplication.translate("MainWindow", u"MainWindow", None))
        self.message_box.setPlaceholderText(QCoreApplication.translate("MainWindow", u"Connecting...", None))
        self.message_input.setPlaceholderText(
            QCoreApplication.translate("MainWindow", u"Type your message here...", None))
        self.message_button.setText(QCoreApplication.translate("MainWindow", u"Send", None))
