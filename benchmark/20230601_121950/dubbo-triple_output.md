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
# Warmup Iteration   1: 0.969 ops/ms
# Warmup Iteration   2: 2.119 ops/ms
# Warmup Iteration   3: 4.637 ops/ms
Iteration   1: 5.247 ops/ms
Iteration   2: 5.586 ops/ms
Iteration   3: 5.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.452 ±(99.9%) 3.293 ops/ms [Average]
  (min, avg, max) = (5.247, 5.452, 5.586), stdev = 0.180
  CI (99.9%): [2.159, 8.745] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.353 ops/ms
# Warmup Iteration   2: 3.952 ops/ms
# Warmup Iteration   3: 5.570 ops/ms
Iteration   1: 5.764 ops/ms
Iteration   2: 5.824 ops/ms
Iteration   3: 5.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.783 ±(99.9%) 0.652 ops/ms [Average]
  (min, avg, max) = (5.760, 5.783, 5.824), stdev = 0.036
  CI (99.9%): [5.131, 6.434] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.378 ops/ms
# Warmup Iteration   2: 4.212 ops/ms
# Warmup Iteration   3: 5.233 ops/ms
Iteration   1: 5.304 ops/ms
Iteration   2: 5.299 ops/ms
Iteration   3: 5.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.431 ±(99.9%) 4.099 ops/ms [Average]
  (min, avg, max) = (5.299, 5.431, 5.691), stdev = 0.225
  CI (99.9%): [1.332, 9.530] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.284 ops/ms
# Warmup Iteration   2: 3.658 ops/ms
# Warmup Iteration   3: 4.646 ops/ms
Iteration   1: 4.675 ops/ms
Iteration   2: 4.585 ops/ms
Iteration   3: 4.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.662 ±(99.9%) 1.304 ops/ms [Average]
  (min, avg, max) = (4.585, 4.662, 4.726), stdev = 0.071
  CI (99.9%): [3.358, 5.966] (assumes normal distribution)


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
# Warmup Iteration   1: 18.933 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 7.594 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.158 ±(99.9%) 0.009 ms/op
Iteration   1: 5.739 ±(99.9%) 0.022 ms/op
Iteration   2: 5.542 ±(99.9%) 0.013 ms/op
Iteration   3: 5.613 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.631 ±(99.9%) 1.825 ms/op [Average]
  (min, avg, max) = (5.542, 5.631, 5.739), stdev = 0.100
  CI (99.9%): [3.806, 7.457] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 18.556 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 6.933 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.686 ±(99.9%) 0.011 ms/op
Iteration   1: 5.487 ±(99.9%) 0.010 ms/op
Iteration   2: 5.507 ±(99.9%) 0.012 ms/op
Iteration   3: 5.623 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.539 ±(99.9%) 1.344 ms/op [Average]
  (min, avg, max) = (5.487, 5.539, 5.623), stdev = 0.074
  CI (99.9%): [4.195, 6.883] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 18.659 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 7.137 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.754 ±(99.9%) 0.010 ms/op
Iteration   1: 5.808 ±(99.9%) 0.009 ms/op
Iteration   2: 5.734 ±(99.9%) 0.011 ms/op
Iteration   3: 5.573 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.705 ±(99.9%) 2.191 ms/op [Average]
  (min, avg, max) = (5.573, 5.705, 5.808), stdev = 0.120
  CI (99.9%): [3.515, 7.896] (assumes normal distribution)


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
# Warmup Iteration   1: 22.419 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 8.499 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 6.898 ±(99.9%) 0.014 ms/op
Iteration   1: 6.765 ±(99.9%) 0.017 ms/op
Iteration   2: 6.751 ±(99.9%) 0.012 ms/op
Iteration   3: 6.744 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.753 ±(99.9%) 0.193 ms/op [Average]
  (min, avg, max) = (6.744, 6.753, 6.765), stdev = 0.011
  CI (99.9%): [6.561, 6.946] (assumes normal distribution)


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
# Warmup Iteration   1: 20.495 ±(99.9%) 0.354 ms/op
# Warmup Iteration   2: 7.768 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.187 ±(99.9%) 0.028 ms/op
Iteration   1: 5.779 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.208 ms/op
                 createUser·p0.50:   5.456 ms/op
                 createUser·p0.90:   7.102 ms/op
                 createUser·p0.95:   8.274 ms/op
                 createUser·p0.99:   11.682 ms/op
                 createUser·p0.999:  25.854 ms/op
                 createUser·p0.9999: 28.735 ms/op
                 createUser·p1.00:   30.736 ms/op

Iteration   2: 5.579 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.384 ms/op
                 createUser·p0.50:   5.349 ms/op
                 createUser·p0.90:   6.693 ms/op
                 createUser·p0.95:   7.414 ms/op
                 createUser·p0.99:   10.043 ms/op
                 createUser·p0.999:  16.894 ms/op
                 createUser·p0.9999: 34.462 ms/op
                 createUser·p1.00:   34.931 ms/op

Iteration   3: 5.716 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.150 ms/op
                 createUser·p0.50:   5.439 ms/op
                 createUser·p0.90:   6.988 ms/op
                 createUser·p0.95:   7.823 ms/op
                 createUser·p0.99:   10.273 ms/op
                 createUser·p0.999:  29.115 ms/op
                 createUser·p0.9999: 32.729 ms/op
                 createUser·p1.00:   32.965 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 168600
  mean =      5.690 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 45951 
    [ 5.000,  7.500) = 112418 
    [ 7.500, 10.000) = 7850 
    [10.000, 12.500) = 1484 
    [12.500, 15.000) = 542 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 56 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.150 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      6.922 ms/op
     p(95.0000) =      7.799 ms/op
     p(99.0000) =     10.813 ms/op
     p(99.9000) =     18.396 ms/op
     p(99.9900) =     33.161 ms/op
     p(99.9990) =     34.886 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 19.239 ±(99.9%) 0.359 ms/op
# Warmup Iteration   2: 8.032 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 5.705 ±(99.9%) 0.023 ms/op
Iteration   1: 5.620 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.964 ms/op
                 existUser·p0.50:   5.243 ms/op
                 existUser·p0.90:   6.988 ms/op
                 existUser·p0.95:   8.201 ms/op
                 existUser·p0.99:   12.141 ms/op
                 existUser·p0.999:  24.084 ms/op
                 existUser·p0.9999: 27.283 ms/op
                 existUser·p1.00:   28.606 ms/op

Iteration   2: 5.517 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.408 ms/op
                 existUser·p0.50:   5.235 ms/op
                 existUser·p0.90:   6.676 ms/op
                 existUser·p0.95:   7.455 ms/op
                 existUser·p0.99:   10.380 ms/op
                 existUser·p0.999:  24.254 ms/op
                 existUser·p0.9999: 28.666 ms/op
                 existUser·p1.00:   29.524 ms/op

Iteration   3: 5.372 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.167 ms/op
                 existUser·p0.50:   5.112 ms/op
                 existUser·p0.90:   6.472 ms/op
                 existUser·p0.95:   7.324 ms/op
                 existUser·p0.99:   9.961 ms/op
                 existUser·p0.999:  19.677 ms/op
                 existUser·p0.9999: 29.852 ms/op
                 existUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 174345
  mean =      5.501 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 66127 
    [ 5.000,  7.500) = 98729 
    [ 7.500, 10.000) = 6837 
    [10.000, 12.500) = 1603 
    [12.500, 15.000) = 509 
    [15.000, 17.500) = 211 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.964 ms/op
     p(50.0000) =      5.186 ms/op
     p(90.0000) =      6.701 ms/op
     p(95.0000) =      7.651 ms/op
     p(99.0000) =     10.986 ms/op
     p(99.9000) =     23.680 ms/op
     p(99.9900) =     28.625 ms/op
     p(99.9990) =     30.239 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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
# Warmup Iteration   1: 19.783 ±(99.9%) 0.376 ms/op
# Warmup Iteration   2: 8.162 ±(99.9%) 0.064 ms/op
# Warmup Iteration   3: 5.878 ±(99.9%) 0.024 ms/op
Iteration   1: 5.690 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.724 ms/op
                 getUser·p0.50:   5.390 ms/op
                 getUser·p0.90:   6.783 ms/op
                 getUser·p0.95:   7.900 ms/op
                 getUser·p0.99:   11.452 ms/op
                 getUser·p0.999:  26.370 ms/op
                 getUser·p0.9999: 33.169 ms/op
                 getUser·p1.00:   33.751 ms/op

Iteration   2: 5.871 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.826 ms/op
                 getUser·p0.50:   5.489 ms/op
                 getUser·p0.90:   7.127 ms/op
                 getUser·p0.95:   8.667 ms/op
                 getUser·p0.99:   12.863 ms/op
                 getUser·p0.999:  27.971 ms/op
                 getUser·p0.9999: 39.096 ms/op
                 getUser·p1.00:   39.911 ms/op

Iteration   3: 5.842 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.961 ms/op
                 getUser·p0.50:   5.546 ms/op
                 getUser·p0.90:   6.988 ms/op
                 getUser·p0.95:   8.298 ms/op
                 getUser·p0.99:   12.075 ms/op
                 getUser·p0.999:  19.035 ms/op
                 getUser·p0.9999: 34.834 ms/op
                 getUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 165340
  mean =      5.800 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 37608 
    [ 5.000,  7.500) = 116022 
    [ 7.500, 10.000) = 7736 
    [10.000, 12.500) = 2516 
    [12.500, 15.000) = 949 
    [15.000, 17.500) = 230 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.724 ms/op
     p(50.0000) =      5.472 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      8.241 ms/op
     p(99.0000) =     12.075 ms/op
     p(99.9000) =     22.795 ms/op
     p(99.9900) =     35.170 ms/op
     p(99.9990) =     39.826 ms/op
     p(99.9999) =     39.911 ms/op
    p(100.0000) =     39.911 ms/op


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
# Warmup Iteration   1: 21.128 ±(99.9%) 0.377 ms/op
# Warmup Iteration   2: 8.360 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 7.012 ±(99.9%) 0.033 ms/op
Iteration   1: 6.757 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   6.316 ms/op
                 listUser·p0.90:   8.290 ms/op
                 listUser·p0.95:   9.929 ms/op
                 listUser·p0.99:   13.730 ms/op
                 listUser·p0.999:  31.642 ms/op
                 listUser·p0.9999: 37.804 ms/op
                 listUser·p1.00:   38.404 ms/op

Iteration   2: 6.688 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   2.949 ms/op
                 listUser·p0.50:   6.169 ms/op
                 listUser·p0.90:   8.389 ms/op
                 listUser·p0.95:   10.158 ms/op
                 listUser·p0.99:   14.352 ms/op
                 listUser·p0.999:  31.621 ms/op
                 listUser·p0.9999: 42.664 ms/op
                 listUser·p1.00:   42.926 ms/op

Iteration   3: 6.855 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.908 ms/op
                 listUser·p0.50:   6.431 ms/op
                 listUser·p0.90:   8.389 ms/op
                 listUser·p0.95:   9.765 ms/op
                 listUser·p0.99:   13.828 ms/op
                 listUser·p0.999:  30.925 ms/op
                 listUser·p0.9999: 35.696 ms/op
                 listUser·p1.00:   37.093 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141809
  mean =      6.766 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3331 
    [ 5.000, 10.000) = 131442 
    [10.000, 15.000) = 6113 
    [15.000, 20.000) = 592 
    [20.000, 25.000) = 29 
    [25.000, 30.000) = 106 
    [30.000, 35.000) = 130 
    [35.000, 40.000) = 45 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      2.257 ms/op
     p(50.0000) =      6.300 ms/op
     p(90.0000) =      8.364 ms/op
     p(95.0000) =      9.978 ms/op
     p(99.0000) =     13.959 ms/op
     p(99.9000) =     31.392 ms/op
     p(99.9900) =     42.336 ms/op
     p(99.9990) =     42.899 ms/op
     p(99.9999) =     42.926 ms/op
    p(100.0000) =     42.926 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.452 ± 3.293  ops/ms
ClientPb.existUser                       thrpt       3   5.783 ± 0.652  ops/ms
ClientPb.getUser                         thrpt       3   5.431 ± 4.099  ops/ms
ClientPb.listUser                        thrpt       3   4.662 ± 1.304  ops/ms
ClientPb.createUser                       avgt       3   5.631 ± 1.825   ms/op
ClientPb.existUser                        avgt       3   5.539 ± 1.344   ms/op
ClientPb.getUser                          avgt       3   5.705 ± 2.191   ms/op
ClientPb.listUser                         avgt       3   6.753 ± 0.193   ms/op
ClientPb.createUser                     sample  168600   5.690 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.150           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.922           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.799           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.813           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.396           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.161           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.931           ms/op
ClientPb.existUser                      sample  174345   5.501 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.964           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.186           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.701           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.651           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.986           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.680           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.625           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.507           ms/op
ClientPb.getUser                        sample  165340   5.800 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.724           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.472           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.971           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.241           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.075           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.795           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.170           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.911           ms/op
ClientPb.listUser                       sample  141809   6.766 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.257           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.300           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.364           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.978           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.959           ms/op
ClientPb.listUser:listUser·p0.999       sample          31.392           ms/op
ClientPb.listUser:listUser·p0.9999      sample          42.336           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.926           ms/op
