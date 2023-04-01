# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.395 ops/ms
# Warmup Iteration   2: 3.042 ops/ms
# Warmup Iteration   3: 5.799 ops/ms
Iteration   1: 5.590 ops/ms
Iteration   2: 5.733 ops/ms
Iteration   3: 5.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.754 ±(99.9%) 3.205 ops/ms [Average]
  (min, avg, max) = (5.590, 5.754, 5.939), stdev = 0.176
  CI (99.9%): [2.549, 8.959] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.837 ops/ms
# Warmup Iteration   2: 5.786 ops/ms
# Warmup Iteration   3: 6.412 ops/ms
Iteration   1: 7.088 ops/ms
Iteration   2: 6.970 ops/ms
Iteration   3: 6.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.921 ±(99.9%) 3.571 ops/ms [Average]
  (min, avg, max) = (6.706, 6.921, 7.088), stdev = 0.196
  CI (99.9%): [3.350, 10.493] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.953 ops/ms
# Warmup Iteration   2: 5.538 ops/ms
# Warmup Iteration   3: 6.386 ops/ms
Iteration   1: 6.242 ops/ms
Iteration   2: 6.361 ops/ms
Iteration   3: 6.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.359 ±(99.9%) 2.123 ops/ms [Average]
  (min, avg, max) = (6.242, 6.359, 6.474), stdev = 0.116
  CI (99.9%): [4.236, 8.482] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.757 ops/ms
# Warmup Iteration   2: 4.499 ops/ms
# Warmup Iteration   3: 5.366 ops/ms
Iteration   1: 5.532 ops/ms
Iteration   2: 5.365 ops/ms
Iteration   3: 5.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.436 ±(99.9%) 1.572 ops/ms [Average]
  (min, avg, max) = (5.365, 5.436, 5.532), stdev = 0.086
  CI (99.9%): [3.864, 7.008] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 16.964 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 5.602 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.390 ±(99.9%) 0.016 ms/op
Iteration   1: 4.990 ±(99.9%) 0.015 ms/op
Iteration   2: 4.891 ±(99.9%) 0.014 ms/op
Iteration   3: 4.957 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.946 ±(99.9%) 0.922 ms/op [Average]
  (min, avg, max) = (4.891, 4.946, 4.990), stdev = 0.051
  CI (99.9%): [4.024, 5.868] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 15.433 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.458 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.895 ±(99.9%) 0.008 ms/op
Iteration   1: 4.862 ±(99.9%) 0.011 ms/op
Iteration   2: 4.828 ±(99.9%) 0.013 ms/op
Iteration   3: 4.882 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.857 ±(99.9%) 0.497 ms/op [Average]
  (min, avg, max) = (4.828, 4.857, 4.882), stdev = 0.027
  CI (99.9%): [4.360, 5.354] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 14.370 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.324 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.131 ±(99.9%) 0.012 ms/op
Iteration   1: 5.236 ±(99.9%) 0.012 ms/op
Iteration   2: 5.187 ±(99.9%) 0.011 ms/op
Iteration   3: 4.899 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.108 ±(99.9%) 3.319 ms/op [Average]
  (min, avg, max) = (4.899, 5.108, 5.236), stdev = 0.182
  CI (99.9%): [1.788, 8.427] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 16.911 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 6.853 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.278 ±(99.9%) 0.015 ms/op
Iteration   1: 6.039 ±(99.9%) 0.014 ms/op
Iteration   2: 5.935 ±(99.9%) 0.016 ms/op
Iteration   3: 5.926 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.967 ±(99.9%) 1.147 ms/op [Average]
  (min, avg, max) = (5.926, 5.967, 6.039), stdev = 0.063
  CI (99.9%): [4.819, 7.114] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.226 ±(99.9%) 0.242 ms/op
# Warmup Iteration   2: 5.885 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.532 ±(99.9%) 0.023 ms/op
Iteration   1: 5.036 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   4.751 ms/op
                 createUser·p0.90:   6.324 ms/op
                 createUser·p0.95:   7.225 ms/op
                 createUser·p0.99:   10.125 ms/op
                 createUser·p0.999:  25.693 ms/op
                 createUser·p0.9999: 28.267 ms/op
                 createUser·p1.00:   30.179 ms/op

Iteration   2: 5.222 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.249 ms/op
                 createUser·p0.50:   4.948 ms/op
                 createUser·p0.90:   6.562 ms/op
                 createUser·p0.95:   7.578 ms/op
                 createUser·p0.99:   9.945 ms/op
                 createUser·p0.999:  25.483 ms/op
                 createUser·p0.9999: 31.436 ms/op
                 createUser·p1.00:   32.571 ms/op

Iteration   3: 5.096 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.300 ms/op
                 createUser·p0.50:   4.825 ms/op
                 createUser·p0.90:   6.341 ms/op
                 createUser·p0.95:   7.152 ms/op
                 createUser·p0.99:   9.486 ms/op
                 createUser·p0.999:  25.919 ms/op
                 createUser·p0.9999: 34.603 ms/op
                 createUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 187634
  mean =      5.117 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 109095 
    [ 5.000,  7.500) = 70326 
    [ 7.500, 10.000) = 6354 
    [10.000, 12.500) = 1334 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      6.414 ms/op
     p(95.0000) =      7.299 ms/op
     p(99.0000) =      9.945 ms/op
     p(99.9000) =     25.592 ms/op
     p(99.9900) =     32.571 ms/op
     p(99.9990) =     34.963 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.213 ±(99.9%) 0.233 ms/op
# Warmup Iteration   2: 5.682 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.042 ±(99.9%) 0.015 ms/op
Iteration   1: 4.816 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.942 ms/op
                 existUser·p0.50:   4.571 ms/op
                 existUser·p0.90:   5.972 ms/op
                 existUser·p0.95:   7.053 ms/op
                 existUser·p0.99:   9.830 ms/op
                 existUser·p0.999:  19.142 ms/op
                 existUser·p0.9999: 26.098 ms/op
                 existUser·p1.00:   26.771 ms/op

Iteration   2: 4.740 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.962 ms/op
                 existUser·p0.50:   4.456 ms/op
                 existUser·p0.90:   5.857 ms/op
                 existUser·p0.95:   6.791 ms/op
                 existUser·p0.99:   9.929 ms/op
                 existUser·p0.999:  18.335 ms/op
                 existUser·p0.9999: 26.526 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   3: 4.773 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.997 ms/op
                 existUser·p0.50:   4.530 ms/op
                 existUser·p0.90:   5.825 ms/op
                 existUser·p0.95:   6.521 ms/op
                 existUser·p0.99:   9.388 ms/op
                 existUser·p0.999:  23.989 ms/op
                 existUser·p0.9999: 31.392 ms/op
                 existUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 200848
  mean =      4.776 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 145429 
    [ 5.000,  7.500) = 49242 
    [ 7.500, 10.000) = 4324 
    [10.000, 12.500) = 1082 
    [12.500, 15.000) = 361 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.942 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.874 ms/op
     p(95.0000) =      6.775 ms/op
     p(99.0000) =      9.765 ms/op
     p(99.9000) =     22.905 ms/op
     p(99.9900) =     30.701 ms/op
     p(99.9990) =     32.532 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.060 ±(99.9%) 0.235 ms/op
# Warmup Iteration   2: 5.376 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.987 ±(99.9%) 0.018 ms/op
Iteration   1: 4.989 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.101 ms/op
                 getUser·p0.50:   4.817 ms/op
                 getUser·p0.90:   5.906 ms/op
                 getUser·p0.95:   6.636 ms/op
                 getUser·p0.99:   8.883 ms/op
                 getUser·p0.999:  19.896 ms/op
                 getUser·p0.9999: 27.367 ms/op
                 getUser·p1.00:   29.262 ms/op

Iteration   2: 5.180 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.318 ms/op
                 getUser·p0.50:   4.915 ms/op
                 getUser·p0.90:   6.373 ms/op
                 getUser·p0.95:   7.619 ms/op
                 getUser·p0.99:   10.355 ms/op
                 getUser·p0.999:  22.841 ms/op
                 getUser·p0.9999: 32.030 ms/op
                 getUser·p1.00:   32.834 ms/op

Iteration   3: 5.074 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.536 ms/op
                 getUser·p0.50:   4.882 ms/op
                 getUser·p0.90:   6.062 ms/op
                 getUser·p0.95:   6.685 ms/op
                 getUser·p0.99:   9.110 ms/op
                 getUser·p0.999:  25.217 ms/op
                 getUser·p0.9999: 33.797 ms/op
                 getUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 188898
  mean =      5.080 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 108390 
    [ 5.000,  7.500) = 73687 
    [ 7.500, 10.000) = 5283 
    [10.000, 12.500) = 1042 
    [12.500, 15.000) = 244 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      6.103 ms/op
     p(95.0000) =      6.963 ms/op
     p(99.0000) =      9.519 ms/op
     p(99.9000) =     20.703 ms/op
     p(99.9900) =     32.862 ms/op
     p(99.9990) =     35.703 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.202 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 6.513 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.966 ±(99.9%) 0.021 ms/op
Iteration   1: 5.931 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.851 ms/op
                 listUser·p0.50:   5.612 ms/op
                 listUser·p0.90:   7.070 ms/op
                 listUser·p0.95:   8.176 ms/op
                 listUser·p0.99:   11.256 ms/op
                 listUser·p0.999:  27.397 ms/op
                 listUser·p0.9999: 31.091 ms/op
                 listUser·p1.00:   31.752 ms/op

Iteration   2: 5.955 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.578 ms/op
                 listUser·p0.50:   5.612 ms/op
                 listUser·p0.90:   7.274 ms/op
                 listUser·p0.95:   8.552 ms/op
                 listUser·p0.99:   11.846 ms/op
                 listUser·p0.999:  22.925 ms/op
                 listUser·p0.9999: 30.278 ms/op
                 listUser·p1.00:   31.228 ms/op

Iteration   3: 5.925 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.630 ms/op
                 listUser·p0.50:   5.652 ms/op
                 listUser·p0.90:   7.021 ms/op
                 listUser·p0.95:   7.978 ms/op
                 listUser·p0.99:   11.682 ms/op
                 listUser·p0.999:  21.070 ms/op
                 listUser·p0.9999: 22.997 ms/op
                 listUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 161581
  mean =      5.937 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 26914 
    [ 5.000,  7.500) = 122483 
    [ 7.500, 10.000) = 8556 
    [10.000, 12.500) = 2472 
    [12.500, 15.000) = 611 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      5.628 ms/op
     p(90.0000) =      7.119 ms/op
     p(95.0000) =      8.281 ms/op
     p(99.0000) =     11.603 ms/op
     p(99.9000) =     23.836 ms/op
     p(99.9900) =     30.278 ms/op
     p(99.9990) =     31.692 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.754 ± 3.205  ops/ms
ClientPb.existUser                       thrpt       3   6.921 ± 3.571  ops/ms
ClientPb.getUser                         thrpt       3   6.359 ± 2.123  ops/ms
ClientPb.listUser                        thrpt       3   5.436 ± 1.572  ops/ms
ClientPb.createUser                       avgt       3   4.946 ± 0.922   ms/op
ClientPb.existUser                        avgt       3   4.857 ± 0.497   ms/op
ClientPb.getUser                          avgt       3   5.108 ± 3.319   ms/op
ClientPb.listUser                         avgt       3   5.967 ± 1.147   ms/op
ClientPb.createUser                     sample  187634   5.117 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.749           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.833           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.414           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.299           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.945           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.592           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.571           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.193           ms/op
ClientPb.existUser                      sample  200848   4.776 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.942           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.514           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.874           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.775           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.765           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.905           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.701           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.539           ms/op
ClientPb.getUser                        sample  188898   5.080 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.536           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.866           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.103           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.963           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.519           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.703           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.862           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.110           ms/op
ClientPb.listUser                       sample  161581   5.937 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.578           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.119           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.281           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.603           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.836           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.278           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.752           ms/op
