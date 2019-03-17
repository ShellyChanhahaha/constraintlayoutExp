# 实验内容

此实验为约束布局的练习

# 关键代码

```xml
<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/red"
        android:layout_width="100dp"
        android:layout_height="70dp"
        android:text="@string/red"
        android:background="@color/RED"
        android:gravity="center"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintStart_toStartOf="parent" />
    <TextView
        android:id="@+id/orange"
        android:layout_width="100dp"
        android:layout_height="70dp"
        android:text="@string/orange"
        android:background="@color/ORANGE"
        android:gravity="center"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <TextView
        android:id="@+id/yellow"
        android:layout_width="100dp"
        android:layout_height="70dp"
        android:text="@string/yellow"
        android:background="@color/YELLOW"
        android:gravity="center"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintEnd_toEndOf="parent" />


    <TextView
        android:id="@+id/green"
        android:layout_width="100dp"
        android:layout_height="70dp"
        android:background="@color/GREEN"
        android:gravity="center"
        android:text="@string/green"
        android:layout_marginLeft="100dp"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintTop_toTopOf="parent"/>

    <TextView
        android:id="@+id/blue"
        android:layout_width="100dp"
        android:layout_height="70dp"
        android:background="@color/BLUE"
        android:gravity="center"
        android:text="@string/blue"
        android:layout_marginLeft="18dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintLeft_toRightOf="@id/green"
        app:layout_constraintRight_toLeftOf="@id/indigo"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <TextView
        android:id="@+id/indigo"
        android:layout_width="100dp"
        android:layout_height="70dp"
        android:layout_marginRight="100dp"
        android:background="@color/INDIGO"
        android:gravity="center"
        android:text="@string/indigo"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <TextView
        android:id="@+id/voilet"
        android:layout_width="0dp"
        android:layout_height="80dp"
        android:layout_marginTop="284dp"
        android:background="@color/VOILET"
        android:gravity="center"
        android:text="@string/violet"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintBottom_toBottomOf="parent" />

</android.support.constraint.ConstraintLayout>
```

# 结果截图

![1552653830709](https://i.loli.net/2019/03/17/5c8d8eabbbb63.png)

