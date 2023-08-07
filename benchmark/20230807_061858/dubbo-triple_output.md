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
# Warmup Iteration   1: 1.071 ops/ms
# Warmup Iteration   2: 2.541 ops/ms
# Warmup Iteration   3: 5.280 ops/ms
Iteration   1: 5.553 ops/ms
Iteration   2: 5.832 ops/ms
Iteration   3: 5.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.765 ±(99.9%) 3.427 ops/ms [Average]
  (min, avg, max) = (5.553, 5.765, 5.911), stdev = 0.188
  CI (99.9%): [2.338, 9.192] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.680 ops/ms
# Warmup Iteration   2: 4.917 ops/ms
# Warmup Iteration   3: 6.089 ops/ms
Iteration   1: 6.211 ops/ms
Iteration   2: 6.224 ops/ms
Iteration   3: 6.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.213 ±(99.9%) 0.183 ops/ms [Average]
  (min, avg, max) = (6.204, 6.213, 6.224), stdev = 0.010
  CI (99.9%): [6.030, 6.396] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.502 ops/ms
# Warmup Iteration   2: 4.535 ops/ms
# Warmup Iteration   3: 5.828 ops/ms
Iteration   1: 5.876 ops/ms
Iteration   2: 6.034 ops/ms
Iteration   3: 6.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.991 ±(99.9%) 1.835 ops/ms [Average]
  (min, avg, max) = (5.876, 5.991, 6.062), stdev = 0.101
  CI (99.9%): [4.155, 7.826] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.635 ops/ms
# Warmup Iteration   2: 4.195 ops/ms
# Warmup Iteration   3: 5.160 ops/ms
Iteration   1: 5.024 ops/ms
Iteration   2: 5.116 ops/ms
Iteration   3: 5.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.113 ±(99.9%) 1.591 ops/ms [Average]
  (min, avg, max) = (5.024, 5.113, 5.199), stdev = 0.087
  CI (99.9%): [3.522, 6.704] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.655 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.380 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.449 ±(99.9%) 0.012 ms/op
Iteration   1: 5.325 ±(99.9%) 0.011 ms/op
Iteration   2: 5.403 ±(99.9%) 0.011 ms/op
Iteration   3: 5.303 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.344 ±(99.9%) 0.959 ms/op [Average]
  (min, avg, max) = (5.303, 5.344, 5.403), stdev = 0.053
  CI (99.9%): [4.385, 6.303] (assumes normal distribution)


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
# Warmup Iteration   1: 16.439 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.692 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.130 ±(99.9%) 0.007 ms/op
Iteration   1: 5.123 ±(99.9%) 0.012 ms/op
Iteration   2: 5.050 ±(99.9%) 0.011 ms/op
Iteration   3: 4.986 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.053 ±(99.9%) 1.250 ms/op [Average]
  (min, avg, max) = (4.986, 5.053, 5.123), stdev = 0.069
  CI (99.9%): [3.804, 6.303] (assumes normal distribution)


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
# Warmup Iteration   1: 16.619 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 6.162 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.278 ±(99.9%) 0.008 ms/op
Iteration   1: 5.244 ±(99.9%) 0.010 ms/op
Iteration   2: 5.150 ±(99.9%) 0.014 ms/op
Iteration   3: 5.157 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.184 ±(99.9%) 0.958 ms/op [Average]
  (min, avg, max) = (5.150, 5.184, 5.244), stdev = 0.053
  CI (99.9%): [4.226, 6.142] (assumes normal distribution)


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
# Warmup Iteration   1: 17.771 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 7.771 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.470 ±(99.9%) 0.010 ms/op
Iteration   1: 6.075 ±(99.9%) 0.018 ms/op
Iteration   2: 5.893 ±(99.9%) 0.014 ms/op
Iteration   3: 5.739 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.902 ±(99.9%) 3.065 ms/op [Average]
  (min, avg, max) = (5.739, 5.902, 6.075), stdev = 0.168
  CI (99.9%): [2.837, 8.968] (assumes normal distribution)


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
# Warmup Iteration   1: 16.056 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 6.760 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.664 ±(99.9%) 0.025 ms/op
Iteration   1: 5.554 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.204 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   7.217 ms/op
                 createUser·p0.95:   8.389 ms/op
                 createUser·p0.99:   11.606 ms/op
                 createUser·p0.999:  25.494 ms/op
                 createUser·p0.9999: 33.283 ms/op
                 createUser·p1.00:   33.751 ms/op

Iteration   2: 5.031 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.077 ms/op
                 createUser·p0.50:   4.776 ms/op
                 createUser·p0.90:   6.259 ms/op
                 createUser·p0.95:   7.209 ms/op
                 createUser·p0.99:   9.765 ms/op
                 createUser·p0.999:  21.864 ms/op
                 createUser·p0.9999: 27.401 ms/op
                 createUser·p1.00:   27.722 ms/op

Iteration   3: 5.174 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.241 ms/op
                 createUser·p0.50:   4.891 ms/op
                 createUser·p0.90:   6.414 ms/op
                 createUser·p0.95:   7.283 ms/op
                 createUser·p0.99:   10.945 ms/op
                 createUser·p0.999:  23.612 ms/op
                 createUser·p0.9999: 27.805 ms/op
                 createUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 182965
  mean =      5.244 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 95929 
    [ 5.000,  7.500) = 76726 
    [ 7.500, 10.000) = 7719 
    [10.000, 12.500) = 1669 
    [12.500, 15.000) = 477 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.077 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      6.586 ms/op
     p(95.0000) =      7.709 ms/op
     p(99.0000) =     10.764 ms/op
     p(99.9000) =     23.399 ms/op
     p(99.9900) =     30.318 ms/op
     p(99.9990) =     33.588 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 15.106 ±(99.9%) 0.241 ms/op
# Warmup Iteration   2: 5.905 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.284 ±(99.9%) 0.022 ms/op
Iteration   1: 4.941 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.392 ms/op
                 existUser·p0.50:   4.612 ms/op
                 existUser·p0.90:   6.308 ms/op
                 existUser·p0.95:   7.176 ms/op
                 existUser·p0.99:   9.814 ms/op
                 existUser·p0.999:  25.730 ms/op
                 existUser·p0.9999: 42.140 ms/op
                 existUser·p1.00:   43.057 ms/op

Iteration   2: 4.739 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.849 ms/op
                 existUser·p0.50:   4.432 ms/op
                 existUser·p0.90:   6.087 ms/op
                 existUser·p0.95:   6.912 ms/op
                 existUser·p0.99:   9.486 ms/op
                 existUser·p0.999:  14.959 ms/op
                 existUser·p0.9999: 26.813 ms/op
                 existUser·p1.00:   29.098 ms/op

Iteration   3: 4.917 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.068 ms/op
                 existUser·p0.50:   4.604 ms/op
                 existUser·p0.90:   6.316 ms/op
                 existUser·p0.95:   7.242 ms/op
                 existUser·p0.99:   9.994 ms/op
                 existUser·p0.999:  14.645 ms/op
                 existUser·p0.9999: 30.572 ms/op
                 existUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 197322
  mean =      4.864 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 134075 
    [ 5.000, 10.000) = 61498 
    [10.000, 15.000) = 1521 
    [15.000, 20.000) = 4 
    [20.000, 25.000) = 40 
    [25.000, 30.000) = 132 
    [30.000, 35.000) = 20 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.849 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      6.242 ms/op
     p(95.0000) =      7.127 ms/op
     p(99.0000) =      9.748 ms/op
     p(99.9000) =     24.773 ms/op
     p(99.9900) =     41.830 ms/op
     p(99.9990) =     42.993 ms/op
     p(99.9999) =     43.057 ms/op
    p(100.0000) =     43.057 ms/op


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
# Warmup Iteration   1: 17.141 ±(99.9%) 0.311 ms/op
# Warmup Iteration   2: 6.518 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.333 ±(99.9%) 0.019 ms/op
Iteration   1: 5.027 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.790 ms/op
                 getUser·p0.50:   4.768 ms/op
                 getUser·p0.90:   6.078 ms/op
                 getUser·p0.95:   7.197 ms/op
                 getUser·p0.99:   9.961 ms/op
                 getUser·p0.999:  26.462 ms/op
                 getUser·p0.9999: 33.882 ms/op
                 getUser·p1.00:   35.586 ms/op

Iteration   2: 5.310 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.384 ms/op
                 getUser·p0.50:   5.038 ms/op
                 getUser·p0.90:   6.373 ms/op
                 getUser·p0.95:   7.791 ms/op
                 getUser·p0.99:   10.928 ms/op
                 getUser·p0.999:  25.054 ms/op
                 getUser·p0.9999: 33.684 ms/op
                 getUser·p1.00:   34.472 ms/op

Iteration   3: 5.273 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.806 ms/op
                 getUser·p0.50:   4.989 ms/op
                 getUser·p0.90:   6.316 ms/op
                 getUser·p0.95:   7.528 ms/op
                 getUser·p0.99:   10.701 ms/op
                 getUser·p0.999:  25.076 ms/op
                 getUser·p0.9999: 31.355 ms/op
                 getUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 184391
  mean =      5.200 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 99488 
    [ 5.000,  7.500) = 75638 
    [ 7.500, 10.000) = 6845 
    [10.000, 12.500) = 1542 
    [12.500, 15.000) = 455 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 39 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.790 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      6.259 ms/op
     p(95.0000) =      7.504 ms/op
     p(99.0000) =     10.600 ms/op
     p(99.9000) =     25.055 ms/op
     p(99.9900) =     33.591 ms/op
     p(99.9990) =     35.475 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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
# Warmup Iteration   1: 17.905 ±(99.9%) 0.270 ms/op
# Warmup Iteration   2: 7.391 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 5.781 ±(99.9%) 0.022 ms/op
Iteration   1: 5.886 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.552 ms/op
                 listUser·p0.50:   5.579 ms/op
                 listUser·p0.90:   7.042 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   11.452 ms/op
                 listUser·p0.999:  25.612 ms/op
                 listUser·p0.9999: 28.989 ms/op
                 listUser·p1.00:   30.507 ms/op

Iteration   2: 6.307 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.142 ms/op
                 listUser·p0.50:   6.005 ms/op
                 listUser·p0.90:   7.430 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   12.423 ms/op
                 listUser·p0.999:  29.785 ms/op
                 listUser·p0.9999: 34.529 ms/op
                 listUser·p1.00:   35.127 ms/op

Iteration   3: 6.175 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   5.833 ms/op
                 listUser·p0.90:   7.479 ms/op
                 listUser·p0.95:   9.028 ms/op
                 listUser·p0.99:   12.534 ms/op
                 listUser·p0.999:  20.046 ms/op
                 listUser·p0.9999: 22.905 ms/op
                 listUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 156810
  mean =      6.117 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 18206 
    [ 5.000,  7.500) = 124551 
    [ 7.500, 10.000) = 9811 
    [10.000, 12.500) = 2892 
    [12.500, 15.000) = 783 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.130 ms/op
     p(50.0000) =      5.808 ms/op
     p(90.0000) =      7.315 ms/op
     p(95.0000) =      8.765 ms/op
     p(99.0000) =     12.042 ms/op
     p(99.9000) =     25.926 ms/op
     p(99.9900) =     33.620 ms/op
     p(99.9990) =     35.090 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.765 ± 3.427  ops/ms
ClientPb.existUser                       thrpt       3   6.213 ± 0.183  ops/ms
ClientPb.getUser                         thrpt       3   5.991 ± 1.835  ops/ms
ClientPb.listUser                        thrpt       3   5.113 ± 1.591  ops/ms
ClientPb.createUser                       avgt       3   5.344 ± 0.959   ms/op
ClientPb.existUser                        avgt       3   5.053 ± 1.250   ms/op
ClientPb.getUser                          avgt       3   5.184 ± 0.958   ms/op
ClientPb.listUser                         avgt       3   5.902 ± 3.065   ms/op
ClientPb.createUser                     sample  182965   5.244 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.077           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.948           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.586           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.709           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.764           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.399           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.318           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.751           ms/op
ClientPb.existUser                      sample  197322   4.864 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.849           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.547           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.242           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.127           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.748           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.773           ms/op
ClientPb.existUser:existUser·p0.9999    sample          41.830           ms/op
ClientPb.existUser:existUser·p1.00      sample          43.057           ms/op
ClientPb.getUser                        sample  184391   5.200 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.790           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.932           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.259           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.504           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.600           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.055           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.591           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.586           ms/op
ClientPb.listUser                       sample  156810   6.117 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.130           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.808           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.315           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.765           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.042           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.926           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.620           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.127           ms/op
