# Note
## git 相关
### arc命令

* arc diff `branchName` --preview  与指定的分支进行diff
* arc land --revision `DiffId` --onto `branchName`  将指定的 diff land 到指定的分支

### Git切换远程
* 修改命令
  * git remote set-url origin `newRemoeteUrl`
  
* 先删除后添加
	* git remote rm origin
   * git remote add origin `newRemoeteUrl`
   
* 修改config
  * cd .git
  * vim config
* `./gradlew assembleRelease generateSourcesJar generatePomFileForAarPublication artifactoryPublish --info ` lib升级