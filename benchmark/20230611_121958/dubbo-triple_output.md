# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.120 ops/ms
# Warmup Iteration   2: 2.373 ops/ms
# Warmup Iteration   3: 5.652 ops/ms
Iteration   1: 5.827 ops/ms
Iteration   2: 6.201 ops/ms
Iteration   3: 6.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.028 ±(99.9%) 3.442 ops/ms [Average]
  (min, avg, max) = (5.827, 6.028, 6.201), stdev = 0.189
  CI (99.9%): [2.586, 9.469] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.453 ops/ms
# Warmup Iteration   2: 4.129 ops/ms
# Warmup Iteration   3: 6.074 ops/ms
Iteration   1: 6.374 ops/ms
Iteration   2: 6.515 ops/ms
Iteration   3: 6.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.392 ±(99.9%) 2.095 ops/ms [Average]
  (min, avg, max) = (6.287, 6.392, 6.515), stdev = 0.115
  CI (99.9%): [4.297, 8.487] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.610 ops/ms
# Warmup Iteration   2: 4.690 ops/ms
# Warmup Iteration   3: 5.764 ops/ms
Iteration   1: 5.870 ops/ms
Iteration   2: 5.824 ops/ms
Iteration   3: 5.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.799 ±(99.9%) 1.584 ops/ms [Average]
  (min, avg, max) = (5.702, 5.799, 5.870), stdev = 0.087
  CI (99.9%): [4.215, 7.383] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.457 ops/ms
# Warmup Iteration   2: 4.076 ops/ms
# Warmup Iteration   3: 5.167 ops/ms
Iteration   1: 5.008 ops/ms
Iteration   2: 4.886 ops/ms
Iteration   3: 5.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.969 ±(99.9%) 1.312 ops/ms [Average]
  (min, avg, max) = (4.886, 4.969, 5.013), stdev = 0.072
  CI (99.9%): [3.657, 6.281] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 19.585 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 6.750 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.523 ±(99.9%) 0.020 ms/op
Iteration   1: 5.335 ±(99.9%) 0.017 ms/op
Iteration   2: 5.198 ±(99.9%) 0.023 ms/op
Iteration   3: 5.406 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.313 ±(99.9%) 1.936 ms/op [Average]
  (min, avg, max) = (5.198, 5.313, 5.406), stdev = 0.106
  CI (99.9%): [3.377, 7.249] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.675 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.725 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.242 ±(99.9%) 0.009 ms/op
Iteration   1: 5.132 ±(99.9%) 0.014 ms/op
Iteration   2: 5.093 ±(99.9%) 0.010 ms/op
Iteration   3: 5.232 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.152 ±(99.9%) 1.309 ms/op [Average]
  (min, avg, max) = (5.093, 5.152, 5.232), stdev = 0.072
  CI (99.9%): [3.844, 6.461] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.131 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.565 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.431 ±(99.9%) 0.009 ms/op
Iteration   1: 5.308 ±(99.9%) 0.011 ms/op
Iteration   2: 5.225 ±(99.9%) 0.009 ms/op
Iteration   3: 5.341 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.291 ±(99.9%) 1.091 ms/op [Average]
  (min, avg, max) = (5.225, 5.291, 5.341), stdev = 0.060
  CI (99.9%): [4.200, 6.382] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.934 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 7.519 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.412 ±(99.9%) 0.016 ms/op
Iteration   1: 6.588 ±(99.9%) 0.008 ms/op
Iteration   2: 6.287 ±(99.9%) 0.011 ms/op
Iteration   3: 6.589 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.488 ±(99.9%) 3.179 ms/op [Average]
  (min, avg, max) = (6.287, 6.488, 6.589), stdev = 0.174
  CI (99.9%): [3.309, 9.667] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 19.033 ±(99.9%) 0.356 ms/op
# Warmup Iteration   2: 7.036 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.078 ±(99.9%) 0.030 ms/op
Iteration   1: 5.715 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.470 ms/op
                 createUser·p0.50:   5.308 ms/op
                 createUser·p0.90:   7.496 ms/op
                 createUser·p0.95:   8.569 ms/op
                 createUser·p0.99:   12.163 ms/op
                 createUser·p0.999:  26.804 ms/op
                 createUser·p0.9999: 29.950 ms/op
                 createUser·p1.00:   31.195 ms/op

Iteration   2: 5.527 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.220 ms/op
                 createUser·p0.50:   5.202 ms/op
                 createUser·p0.90:   6.889 ms/op
                 createUser·p0.95:   7.897 ms/op
                 createUser·p0.99:   11.410 ms/op
                 createUser·p0.999:  29.487 ms/op
                 createUser·p0.9999: 36.831 ms/op
                 createUser·p1.00:   37.028 ms/op

Iteration   3: 5.424 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.138 ms/op
                 createUser·p0.50:   5.177 ms/op
                 createUser·p0.90:   6.611 ms/op
                 createUser·p0.95:   7.471 ms/op
                 createUser·p0.99:   10.109 ms/op
                 createUser·p0.999:  16.762 ms/op
                 createUser·p0.9999: 33.361 ms/op
                 createUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 172973
  mean =      5.552 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 62559 
    [ 5.000,  7.500) = 98167 
    [ 7.500, 10.000) = 9373 
    [10.000, 12.500) = 1871 
    [12.500, 15.000) = 656 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      2.138 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      6.996 ms/op
     p(95.0000) =      8.053 ms/op
     p(99.0000) =     11.305 ms/op
     p(99.9000) =     19.858 ms/op
     p(99.9900) =     35.894 ms/op
     p(99.9990) =     36.980 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.325 ±(99.9%) 0.253 ms/op
# Warmup Iteration   2: 6.230 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.488 ±(99.9%) 0.022 ms/op
Iteration   1: 5.269 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.923 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   6.537 ms/op
                 existUser·p0.95:   7.594 ms/op
                 existUser·p0.99:   10.420 ms/op
                 existUser·p0.999:  28.364 ms/op
                 existUser·p0.9999: 33.061 ms/op
                 existUser·p1.00:   39.256 ms/op

Iteration   2: 5.253 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.937 ms/op
                 existUser·p0.50:   4.981 ms/op
                 existUser·p0.90:   6.504 ms/op
                 existUser·p0.95:   7.561 ms/op
                 existUser·p0.99:   10.273 ms/op
                 existUser·p0.999:  20.152 ms/op
                 existUser·p0.9999: 32.039 ms/op
                 existUser·p1.00:   32.866 ms/op

Iteration   3: 5.328 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.911 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.652 ms/op
                 existUser·p0.95:   7.602 ms/op
                 existUser·p0.99:   10.060 ms/op
                 existUser·p0.999:  28.803 ms/op
                 existUser·p0.9999: 33.423 ms/op
                 existUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 181554
  mean =      5.283 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 93560 
    [ 5.000,  7.500) = 78330 
    [ 7.500, 10.000) = 7594 
    [10.000, 12.500) = 1333 
    [12.500, 15.000) = 386 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 85 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.911 ms/op
     p(50.0000) =      4.981 ms/op
     p(90.0000) =      6.562 ms/op
     p(95.0000) =      7.586 ms/op
     p(99.0000) =     10.256 ms/op
     p(99.9000) =     27.045 ms/op
     p(99.9900) =     32.922 ms/op
     p(99.9990) =     39.149 ms/op
     p(99.9999) =     39.256 ms/op
    p(100.0000) =     39.256 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.651 ±(99.9%) 0.270 ms/op
# Warmup Iteration   2: 6.235 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.697 ±(99.9%) 0.024 ms/op
Iteration   1: 5.720 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.757 ms/op
                 getUser·p0.50:   5.276 ms/op
                 getUser·p0.90:   7.619 ms/op
                 getUser·p0.95:   8.880 ms/op
                 getUser·p0.99:   11.633 ms/op
                 getUser·p0.999:  22.915 ms/op
                 getUser·p0.9999: 27.702 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   2: 5.625 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   2.257 ms/op
                 getUser·p0.50:   5.153 ms/op
                 getUser·p0.90:   7.127 ms/op
                 getUser·p0.95:   8.749 ms/op
                 getUser·p0.99:   12.976 ms/op
                 getUser·p0.999:  33.108 ms/op
                 getUser·p0.9999: 35.914 ms/op
                 getUser·p1.00:   38.666 ms/op

Iteration   3: 5.595 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.937 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   7.242 ms/op
                 getUser·p0.95:   8.380 ms/op
                 getUser·p0.99:   10.322 ms/op
                 getUser·p0.999:  14.214 ms/op
                 getUser·p0.9999: 31.874 ms/op
                 getUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 169916
  mean =      5.646 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 61000 
    [ 5.000,  7.500) = 93264 
    [ 7.500, 10.000) = 11874 
    [10.000, 12.500) = 2571 
    [12.500, 15.000) = 755 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 60 
    [32.500, 35.000) = 50 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.937 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      7.332 ms/op
     p(95.0000) =      8.602 ms/op
     p(99.0000) =     11.649 ms/op
     p(99.9000) =     23.465 ms/op
     p(99.9900) =     35.062 ms/op
     p(99.9990) =     38.529 ms/op
     p(99.9999) =     38.666 ms/op
    p(100.0000) =     38.666 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.211 ±(99.9%) 0.333 ms/op
# Warmup Iteration   2: 7.106 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.363 ±(99.9%) 0.026 ms/op
Iteration   1: 6.221 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.519 ms/op
                 listUser·p0.50:   5.784 ms/op
                 listUser·p0.90:   7.725 ms/op
                 listUser·p0.95:   8.765 ms/op
                 listUser·p0.99:   12.911 ms/op
                 listUser·p0.999:  32.480 ms/op
                 listUser·p0.9999: 36.551 ms/op
                 listUser·p1.00:   38.207 ms/op

Iteration   2: 5.914 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   5.554 ms/op
                 listUser·p0.90:   7.266 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   10.994 ms/op
                 listUser·p0.999:  28.659 ms/op
                 listUser·p0.9999: 42.513 ms/op
                 listUser·p1.00:   44.237 ms/op

Iteration   3: 6.179 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.579 ms/op
                 listUser·p0.50:   5.734 ms/op
                 listUser·p0.90:   7.954 ms/op
                 listUser·p0.95:   9.404 ms/op
                 listUser·p0.99:   12.239 ms/op
                 listUser·p0.999:  22.945 ms/op
                 listUser·p0.9999: 25.384 ms/op
                 listUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 157297
  mean =      6.101 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 22294 
    [ 5.000, 10.000) = 130405 
    [10.000, 15.000) = 3985 
    [15.000, 20.000) = 288 
    [20.000, 25.000) = 116 
    [25.000, 30.000) = 109 
    [30.000, 35.000) = 56 
    [35.000, 40.000) = 37 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      5.693 ms/op
     p(90.0000) =      7.660 ms/op
     p(95.0000) =      8.847 ms/op
     p(99.0000) =     12.108 ms/op
     p(99.9000) =     27.309 ms/op
     p(99.9900) =     36.998 ms/op
     p(99.9990) =     43.636 ms/op
     p(99.9999) =     44.237 ms/op
    p(100.0000) =     44.237 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.028 ± 3.442  ops/ms
ClientPb.existUser                       thrpt       3   6.392 ± 2.095  ops/ms
ClientPb.getUser                         thrpt       3   5.799 ± 1.584  ops/ms
ClientPb.listUser                        thrpt       3   4.969 ± 1.312  ops/ms
ClientPb.createUser                       avgt       3   5.313 ± 1.936   ms/op
ClientPb.existUser                        avgt       3   5.152 ± 1.309   ms/op
ClientPb.getUser                          avgt       3   5.291 ± 1.091   ms/op
ClientPb.listUser                         avgt       3   6.488 ± 3.179   ms/op
ClientPb.createUser                     sample  172973   5.552 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.138           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.226           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.996           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.053           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.305           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.858           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.894           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.028           ms/op
ClientPb.existUser                      sample  181554   5.283 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.911           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.981           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.562           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.586           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.256           ms/op
ClientPb.existUser:existUser·p0.999     sample          27.045           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.922           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.256           ms/op
ClientPb.getUser                        sample  169916   5.646 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.937           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.226           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.332           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.602           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.649           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.465           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.062           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.666           ms/op
ClientPb.listUser                       sample  157297   6.101 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.579           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.660           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.847           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.108           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.309           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.998           ms/op
ClientPb.listUser:listUser·p1.00        sample          44.237           ms/op
