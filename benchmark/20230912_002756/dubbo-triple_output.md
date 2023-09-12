# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.219 ops/ms
# Warmup Iteration   2: 2.488 ops/ms
# Warmup Iteration   3: 4.675 ops/ms
Iteration   1: 5.654 ops/ms
Iteration   2: 5.855 ops/ms
Iteration   3: 6.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.844 ±(99.9%) 3.369 ops/ms [Average]
  (min, avg, max) = (5.654, 5.844, 6.023), stdev = 0.185
  CI (99.9%): [2.475, 9.213] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.753 ops/ms
# Warmup Iteration   2: 4.987 ops/ms
# Warmup Iteration   3: 6.069 ops/ms
Iteration   1: 6.387 ops/ms
Iteration   2: 6.470 ops/ms
Iteration   3: 6.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.415 ±(99.9%) 0.867 ops/ms [Average]
  (min, avg, max) = (6.387, 6.415, 6.470), stdev = 0.048
  CI (99.9%): [5.548, 7.282] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.776 ops/ms
# Warmup Iteration   2: 4.694 ops/ms
# Warmup Iteration   3: 5.679 ops/ms
Iteration   1: 5.953 ops/ms
Iteration   2: 6.002 ops/ms
Iteration   3: 6.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.002 ±(99.9%) 0.885 ops/ms [Average]
  (min, avg, max) = (5.953, 6.002, 6.050), stdev = 0.049
  CI (99.9%): [5.116, 6.887] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.735 ops/ms
# Warmup Iteration   2: 4.231 ops/ms
# Warmup Iteration   3: 5.040 ops/ms
Iteration   1: 5.106 ops/ms
Iteration   2: 4.975 ops/ms
Iteration   3: 5.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.086 ±(99.9%) 1.862 ops/ms [Average]
  (min, avg, max) = (4.975, 5.086, 5.176), stdev = 0.102
  CI (99.9%): [3.224, 6.948] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 16.179 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.709 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.440 ±(99.9%) 0.007 ms/op
Iteration   1: 5.212 ±(99.9%) 0.013 ms/op
Iteration   2: 5.169 ±(99.9%) 0.009 ms/op
Iteration   3: 5.175 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.185 ±(99.9%) 0.432 ms/op [Average]
  (min, avg, max) = (5.169, 5.185, 5.212), stdev = 0.024
  CI (99.9%): [4.753, 5.617] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 15.983 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.863 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.446 ±(99.9%) 0.005 ms/op
Iteration   1: 5.110 ±(99.9%) 0.007 ms/op
Iteration   2: 4.928 ±(99.9%) 0.014 ms/op
Iteration   3: 4.954 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.997 ±(99.9%) 1.797 ms/op [Average]
  (min, avg, max) = (4.928, 4.997, 5.110), stdev = 0.098
  CI (99.9%): [3.201, 6.794] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.868 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 6.371 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.420 ±(99.9%) 0.011 ms/op
Iteration   1: 5.255 ±(99.9%) 0.012 ms/op
Iteration   2: 5.121 ±(99.9%) 0.016 ms/op
Iteration   3: 5.163 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.180 ±(99.9%) 1.257 ms/op [Average]
  (min, avg, max) = (5.121, 5.180, 5.255), stdev = 0.069
  CI (99.9%): [3.922, 6.437] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 19.419 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 6.817 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.266 ±(99.9%) 0.009 ms/op
Iteration   1: 5.927 ±(99.9%) 0.017 ms/op
Iteration   2: 5.868 ±(99.9%) 0.012 ms/op
Iteration   3: 6.092 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.962 ±(99.9%) 2.121 ms/op [Average]
  (min, avg, max) = (5.868, 5.962, 6.092), stdev = 0.116
  CI (99.9%): [3.841, 8.084] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 15.100 ±(99.9%) 0.259 ms/op
# Warmup Iteration   2: 6.729 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.563 ±(99.9%) 0.023 ms/op
Iteration   1: 5.306 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.187 ms/op
                 createUser·p0.50:   5.022 ms/op
                 createUser·p0.90:   6.586 ms/op
                 createUser·p0.95:   7.774 ms/op
                 createUser·p0.99:   10.027 ms/op
                 createUser·p0.999:  21.584 ms/op
                 createUser·p0.9999: 29.685 ms/op
                 createUser·p1.00:   30.376 ms/op

Iteration   2: 5.213 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   4.940 ms/op
                 createUser·p0.90:   6.308 ms/op
                 createUser·p0.95:   7.045 ms/op
                 createUser·p0.99:   9.929 ms/op
                 createUser·p0.999:  26.387 ms/op
                 createUser·p0.9999: 32.534 ms/op
                 createUser·p1.00:   34.144 ms/op

Iteration   3: 5.001 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.433 ms/op
                 createUser·p0.50:   4.743 ms/op
                 createUser·p0.90:   6.038 ms/op
                 createUser·p0.95:   6.717 ms/op
                 createUser·p0.99:   9.437 ms/op
                 createUser·p0.999:  27.662 ms/op
                 createUser·p0.9999: 36.478 ms/op
                 createUser·p1.00:   40.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 185587
  mean =      5.170 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 105831 
    [ 5.000, 10.000) = 78094 
    [10.000, 15.000) = 1261 
    [15.000, 20.000) = 157 
    [20.000, 25.000) = 74 
    [25.000, 30.000) = 85 
    [30.000, 35.000) = 63 
    [35.000, 40.000) = 20 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.464 ms/op
     p(50.0000) =      4.874 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      7.209 ms/op
     p(99.0000) =      9.798 ms/op
     p(99.9000) =     24.370 ms/op
     p(99.9900) =     35.652 ms/op
     p(99.9990) =     40.333 ms/op
     p(99.9999) =     40.501 ms/op
    p(100.0000) =     40.501 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.192 ±(99.9%) 0.219 ms/op
# Warmup Iteration   2: 5.691 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.114 ±(99.9%) 0.018 ms/op
Iteration   1: 4.963 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.224 ms/op
                 existUser·p0.50:   4.661 ms/op
                 existUser·p0.90:   6.038 ms/op
                 existUser·p0.95:   7.111 ms/op
                 existUser·p0.99:   9.978 ms/op
                 existUser·p0.999:  20.761 ms/op
                 existUser·p0.9999: 26.637 ms/op
                 existUser·p1.00:   27.787 ms/op

Iteration   2: 5.018 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.351 ms/op
                 existUser·p0.50:   4.735 ms/op
                 existUser·p0.90:   6.144 ms/op
                 existUser·p0.95:   7.070 ms/op
                 existUser·p0.99:   9.257 ms/op
                 existUser·p0.999:  24.764 ms/op
                 existUser·p0.9999: 29.000 ms/op
                 existUser·p1.00:   29.917 ms/op

Iteration   3: 4.983 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.030 ms/op
                 existUser·p0.50:   4.751 ms/op
                 existUser·p0.90:   5.964 ms/op
                 existUser·p0.95:   6.701 ms/op
                 existUser·p0.99:   8.804 ms/op
                 existUser·p0.999:  24.071 ms/op
                 existUser·p0.9999: 29.882 ms/op
                 existUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 192338
  mean =      4.988 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 127674 
    [ 5.000,  7.500) = 57835 
    [ 7.500, 10.000) = 5332 
    [10.000, 12.500) = 823 
    [12.500, 15.000) = 299 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.030 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      6.046 ms/op
     p(95.0000) =      6.971 ms/op
     p(99.0000) =      9.421 ms/op
     p(99.9000) =     20.764 ms/op
     p(99.9900) =     29.287 ms/op
     p(99.9990) =     31.455 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.824 ±(99.9%) 0.269 ms/op
# Warmup Iteration   2: 5.688 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.433 ±(99.9%) 0.022 ms/op
Iteration   1: 5.253 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.322 ms/op
                 getUser·p0.50:   5.005 ms/op
                 getUser·p0.90:   6.070 ms/op
                 getUser·p0.95:   7.324 ms/op
                 getUser·p0.99:   10.786 ms/op
                 getUser·p0.999:  24.052 ms/op
                 getUser·p0.9999: 26.608 ms/op
                 getUser·p1.00:   27.787 ms/op

Iteration   2: 5.176 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.241 ms/op
                 getUser·p0.50:   4.956 ms/op
                 getUser·p0.90:   6.250 ms/op
                 getUser·p0.95:   6.955 ms/op
                 getUser·p0.99:   9.322 ms/op
                 getUser·p0.999:  23.469 ms/op
                 getUser·p0.9999: 27.846 ms/op
                 getUser·p1.00:   28.213 ms/op

Iteration   3: 5.085 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.937 ms/op
                 getUser·p0.50:   4.899 ms/op
                 getUser·p0.90:   5.882 ms/op
                 getUser·p0.95:   6.409 ms/op
                 getUser·p0.99:   9.591 ms/op
                 getUser·p0.999:  24.953 ms/op
                 getUser·p0.9999: 29.440 ms/op
                 getUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 185477
  mean =      5.170 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 98063 
    [ 5.000,  7.500) = 80974 
    [ 7.500, 10.000) = 4681 
    [10.000, 12.500) = 1052 
    [12.500, 15.000) = 350 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 98 

  Percentiles, ms/op:
      p(0.0000) =      1.937 ms/op
     p(50.0000) =      4.956 ms/op
     p(90.0000) =      6.070 ms/op
     p(95.0000) =      6.816 ms/op
     p(99.0000) =      9.896 ms/op
     p(99.9000) =     23.921 ms/op
     p(99.9900) =     28.451 ms/op
     p(99.9990) =     29.697 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.783 ±(99.9%) 0.307 ms/op
# Warmup Iteration   2: 8.387 ±(99.9%) 0.064 ms/op
# Warmup Iteration   3: 6.204 ±(99.9%) 0.025 ms/op
Iteration   1: 6.261 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.826 ms/op
                 listUser·p0.50:   5.890 ms/op
                 listUser·p0.90:   7.602 ms/op
                 listUser·p0.95:   9.339 ms/op
                 listUser·p0.99:   11.784 ms/op
                 listUser·p0.999:  28.208 ms/op
                 listUser·p0.9999: 33.143 ms/op
                 listUser·p1.00:   34.275 ms/op

Iteration   2: 6.357 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   5.964 ms/op
                 listUser·p0.90:   7.840 ms/op
                 listUser·p0.95:   9.060 ms/op
                 listUser·p0.99:   11.452 ms/op
                 listUser·p0.999:  31.392 ms/op
                 listUser·p0.9999: 33.880 ms/op
                 listUser·p1.00:   34.603 ms/op

Iteration   3: 6.369 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.994 ms/op
                 listUser·p0.50:   6.005 ms/op
                 listUser·p0.90:   8.004 ms/op
                 listUser·p0.95:   9.126 ms/op
                 listUser·p0.99:   12.706 ms/op
                 listUser·p0.999:  21.422 ms/op
                 listUser·p0.9999: 28.409 ms/op
                 listUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151655
  mean =      6.329 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 9821 
    [ 5.000,  7.500) = 123308 
    [ 7.500, 10.000) = 13994 
    [10.000, 12.500) = 3264 
    [12.500, 15.000) = 667 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 44 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.245 ms/op
     p(50.0000) =      5.947 ms/op
     p(90.0000) =      7.823 ms/op
     p(95.0000) =      9.159 ms/op
     p(99.0000) =     12.009 ms/op
     p(99.9000) =     27.143 ms/op
     p(99.9900) =     33.451 ms/op
     p(99.9990) =     34.468 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.844 ± 3.369  ops/ms
ClientPb.existUser                       thrpt       3   6.415 ± 0.867  ops/ms
ClientPb.getUser                         thrpt       3   6.002 ± 0.885  ops/ms
ClientPb.listUser                        thrpt       3   5.086 ± 1.862  ops/ms
ClientPb.createUser                       avgt       3   5.185 ± 0.432   ms/op
ClientPb.existUser                        avgt       3   4.997 ± 1.797   ms/op
ClientPb.getUser                          avgt       3   5.180 ± 1.257   ms/op
ClientPb.listUser                         avgt       3   5.962 ± 2.121   ms/op
ClientPb.createUser                     sample  185587   5.170 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.464           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.874           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.308           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.209           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.798           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.370           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.652           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.501           ms/op
ClientPb.existUser                      sample  192338   4.988 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.030           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.719           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.046           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.971           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.421           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.764           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.287           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.818           ms/op
ClientPb.getUser                        sample  185477   5.170 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.937           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.956           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.070           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.816           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.896           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.921           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.451           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.753           ms/op
ClientPb.listUser                       sample  151655   6.329 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.245           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.947           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.823           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.159           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.009           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.143           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.451           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.603           ms/op
