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
# Warmup Iteration   1: 1.099 ops/ms
# Warmup Iteration   2: 2.326 ops/ms
# Warmup Iteration   3: 5.276 ops/ms
Iteration   1: 5.166 ops/ms
Iteration   2: 5.722 ops/ms
Iteration   3: 5.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.570 ±(99.9%) 6.441 ops/ms [Average]
  (min, avg, max) = (5.166, 5.570, 5.821), stdev = 0.353
  CI (99.9%): [≈ 0, 12.011] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.824 ops/ms
# Warmup Iteration   2: 4.924 ops/ms
# Warmup Iteration   3: 5.699 ops/ms
Iteration   1: 6.133 ops/ms
Iteration   2: 6.329 ops/ms
Iteration   3: 5.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.093 ±(99.9%) 4.721 ops/ms [Average]
  (min, avg, max) = (5.816, 6.093, 6.329), stdev = 0.259
  CI (99.9%): [1.372, 10.814] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.629 ops/ms
# Warmup Iteration   2: 4.651 ops/ms
# Warmup Iteration   3: 5.569 ops/ms
Iteration   1: 5.623 ops/ms
Iteration   2: 5.606 ops/ms
Iteration   3: 5.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.705 ±(99.9%) 2.859 ops/ms [Average]
  (min, avg, max) = (5.606, 5.705, 5.886), stdev = 0.157
  CI (99.9%): [2.846, 8.564] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.701 ops/ms
# Warmup Iteration   2: 3.581 ops/ms
# Warmup Iteration   3: 4.762 ops/ms
Iteration   1: 4.806 ops/ms
Iteration   2: 4.994 ops/ms
Iteration   3: 4.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.875 ±(99.9%) 1.886 ops/ms [Average]
  (min, avg, max) = (4.806, 4.875, 4.994), stdev = 0.103
  CI (99.9%): [2.989, 6.761] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 17.866 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 6.691 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.877 ±(99.9%) 0.012 ms/op
Iteration   1: 5.568 ±(99.9%) 0.010 ms/op
Iteration   2: 5.592 ±(99.9%) 0.012 ms/op
Iteration   3: 5.712 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.624 ±(99.9%) 1.403 ms/op [Average]
  (min, avg, max) = (5.568, 5.624, 5.712), stdev = 0.077
  CI (99.9%): [4.221, 7.027] (assumes normal distribution)


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
# Warmup Iteration   1: 17.187 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.155 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.585 ±(99.9%) 0.012 ms/op
Iteration   1: 5.548 ±(99.9%) 0.010 ms/op
Iteration   2: 5.099 ±(99.9%) 0.012 ms/op
Iteration   3: 5.553 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.400 ±(99.9%) 4.760 ms/op [Average]
  (min, avg, max) = (5.099, 5.400, 5.553), stdev = 0.261
  CI (99.9%): [0.640, 10.160] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 17.007 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.902 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.610 ±(99.9%) 0.015 ms/op
Iteration   1: 5.600 ±(99.9%) 0.020 ms/op
Iteration   2: 5.590 ±(99.9%) 0.013 ms/op
Iteration   3: 5.657 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.616 ±(99.9%) 0.658 ms/op [Average]
  (min, avg, max) = (5.590, 5.616, 5.657), stdev = 0.036
  CI (99.9%): [4.958, 6.274] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.924 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 7.842 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.683 ±(99.9%) 0.009 ms/op
Iteration   1: 6.394 ±(99.9%) 0.016 ms/op
Iteration   2: 6.394 ±(99.9%) 0.013 ms/op
Iteration   3: 6.547 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.445 ±(99.9%) 1.611 ms/op [Average]
  (min, avg, max) = (6.394, 6.445, 6.547), stdev = 0.088
  CI (99.9%): [4.834, 8.056] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.003 ±(99.9%) 0.277 ms/op
# Warmup Iteration   2: 6.889 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 6.281 ±(99.9%) 0.028 ms/op
Iteration   1: 5.830 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.392 ms/op
                 createUser·p0.50:   5.677 ms/op
                 createUser·p0.90:   7.242 ms/op
                 createUser·p0.95:   8.045 ms/op
                 createUser·p0.99:   10.109 ms/op
                 createUser·p0.999:  24.700 ms/op
                 createUser·p0.9999: 27.788 ms/op
                 createUser·p1.00:   29.196 ms/op

Iteration   2: 5.861 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.699 ms/op
                 createUser·p0.50:   5.693 ms/op
                 createUser·p0.90:   7.160 ms/op
                 createUser·p0.95:   7.832 ms/op
                 createUser·p0.99:   10.880 ms/op
                 createUser·p0.999:  28.885 ms/op
                 createUser·p0.9999: 37.058 ms/op
                 createUser·p1.00:   37.945 ms/op

Iteration   3: 5.862 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.556 ms/op
                 createUser·p0.50:   5.726 ms/op
                 createUser·p0.90:   7.062 ms/op
                 createUser·p0.95:   7.881 ms/op
                 createUser·p0.99:   10.113 ms/op
                 createUser·p0.999:  19.300 ms/op
                 createUser·p0.9999: 31.926 ms/op
                 createUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 163857
  mean =      5.851 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 38693 
    [ 5.000,  7.500) = 113411 
    [ 7.500, 10.000) = 9867 
    [10.000, 12.500) = 1101 
    [12.500, 15.000) = 380 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.392 ms/op
     p(50.0000) =      5.702 ms/op
     p(90.0000) =      7.152 ms/op
     p(95.0000) =      7.930 ms/op
     p(99.0000) =     10.289 ms/op
     p(99.9000) =     25.760 ms/op
     p(99.9900) =     34.578 ms/op
     p(99.9990) =     37.903 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.973 ±(99.9%) 0.260 ms/op
# Warmup Iteration   2: 6.365 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.757 ±(99.9%) 0.022 ms/op
Iteration   1: 5.607 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.388 ms/op
                 existUser·p0.50:   5.349 ms/op
                 existUser·p0.90:   7.143 ms/op
                 existUser·p0.95:   7.954 ms/op
                 existUser·p0.99:   10.236 ms/op
                 existUser·p0.999:  16.023 ms/op
                 existUser·p0.9999: 26.886 ms/op
                 existUser·p1.00:   27.656 ms/op

Iteration   2: 5.641 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.175 ms/op
                 existUser·p0.50:   5.464 ms/op
                 existUser·p0.90:   6.816 ms/op
                 existUser·p0.95:   7.668 ms/op
                 existUser·p0.99:   10.715 ms/op
                 existUser·p0.999:  26.214 ms/op
                 existUser·p0.9999: 30.954 ms/op
                 existUser·p1.00:   31.621 ms/op

Iteration   3: 5.522 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.281 ms/op
                 existUser·p0.50:   5.235 ms/op
                 existUser·p0.90:   6.849 ms/op
                 existUser·p0.95:   7.660 ms/op
                 existUser·p0.99:   9.929 ms/op
                 existUser·p0.999:  27.525 ms/op
                 existUser·p0.9999: 31.562 ms/op
                 existUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 171664
  mean =      5.589 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 56814 
    [ 5.000,  7.500) = 104109 
    [ 7.500, 10.000) = 8772 
    [10.000, 12.500) = 1300 
    [12.500, 15.000) = 330 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.175 ms/op
     p(50.0000) =      5.358 ms/op
     p(90.0000) =      6.939 ms/op
     p(95.0000) =      7.791 ms/op
     p(99.0000) =     10.224 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     30.933 ms/op
     p(99.9990) =     32.492 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 16.823 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 7.229 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.516 ±(99.9%) 0.020 ms/op
Iteration   1: 5.768 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.621 ms/op
                 getUser·p0.50:   5.448 ms/op
                 getUser·p0.90:   7.274 ms/op
                 getUser·p0.95:   8.143 ms/op
                 getUser·p0.99:   10.502 ms/op
                 getUser·p0.999:  23.724 ms/op
                 getUser·p0.9999: 27.409 ms/op
                 getUser·p1.00:   30.441 ms/op

Iteration   2: 5.500 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.675 ms/op
                 getUser·p0.50:   5.226 ms/op
                 getUser·p0.90:   6.832 ms/op
                 getUser·p0.95:   7.348 ms/op
                 getUser·p0.99:   8.831 ms/op
                 getUser·p0.999:  20.079 ms/op
                 getUser·p0.9999: 29.890 ms/op
                 getUser·p1.00:   30.867 ms/op

Iteration   3: 5.703 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.495 ms/op
                 getUser·p0.50:   5.571 ms/op
                 getUser·p0.90:   6.914 ms/op
                 getUser·p0.95:   7.651 ms/op
                 getUser·p0.99:   10.064 ms/op
                 getUser·p0.999:  26.640 ms/op
                 getUser·p0.9999: 36.621 ms/op
                 getUser·p1.00:   37.159 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 169739
  mean =      5.654 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 60864 
    [ 5.000,  7.500) = 98797 
    [ 7.500, 10.000) = 8568 
    [10.000, 12.500) = 971 
    [12.500, 15.000) = 224 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.495 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      6.988 ms/op
     p(95.0000) =      7.700 ms/op
     p(99.0000) =      9.798 ms/op
     p(99.9000) =     21.496 ms/op
     p(99.9900) =     34.801 ms/op
     p(99.9990) =     37.068 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


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
# Warmup Iteration   1: 19.633 ±(99.9%) 0.339 ms/op
# Warmup Iteration   2: 8.341 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 6.904 ±(99.9%) 0.028 ms/op
Iteration   1: 6.669 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.825 ms/op
                 listUser·p0.50:   6.332 ms/op
                 listUser·p0.90:   8.348 ms/op
                 listUser·p0.95:   9.175 ms/op
                 listUser·p0.99:   11.829 ms/op
                 listUser·p0.999:  27.134 ms/op
                 listUser·p0.9999: 39.013 ms/op
                 listUser·p1.00:   41.026 ms/op

Iteration   2: 6.787 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   6.480 ms/op
                 listUser·p0.90:   8.225 ms/op
                 listUser·p0.95:   9.191 ms/op
                 listUser·p0.99:   12.091 ms/op
                 listUser·p0.999:  32.532 ms/op
                 listUser·p0.9999: 36.999 ms/op
                 listUser·p1.00:   37.814 ms/op

Iteration   3: 6.869 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   6.586 ms/op
                 listUser·p0.90:   8.405 ms/op
                 listUser·p0.95:   9.667 ms/op
                 listUser·p0.99:   12.567 ms/op
                 listUser·p0.999:  30.046 ms/op
                 listUser·p0.9999: 36.920 ms/op
                 listUser·p1.00:   37.945 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141671
  mean =      6.774 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3844 
    [ 5.000, 10.000) = 133132 
    [10.000, 15.000) = 4243 
    [15.000, 20.000) = 156 
    [20.000, 25.000) = 42 
    [25.000, 30.000) = 111 
    [30.000, 35.000) = 89 
    [35.000, 40.000) = 51 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.825 ms/op
     p(50.0000) =      6.472 ms/op
     p(90.0000) =      8.323 ms/op
     p(95.0000) =      9.322 ms/op
     p(99.0000) =     12.124 ms/op
     p(99.9000) =     30.103 ms/op
     p(99.9900) =     37.814 ms/op
     p(99.9990) =     40.643 ms/op
     p(99.9999) =     41.026 ms/op
    p(100.0000) =     41.026 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.570 ± 6.441  ops/ms
ClientPb.existUser                       thrpt       3   6.093 ± 4.721  ops/ms
ClientPb.getUser                         thrpt       3   5.705 ± 2.859  ops/ms
ClientPb.listUser                        thrpt       3   4.875 ± 1.886  ops/ms
ClientPb.createUser                       avgt       3   5.624 ± 1.403   ms/op
ClientPb.existUser                        avgt       3   5.400 ± 4.760   ms/op
ClientPb.getUser                          avgt       3   5.616 ± 0.658   ms/op
ClientPb.listUser                         avgt       3   6.445 ± 1.611   ms/op
ClientPb.createUser                     sample  163857   5.851 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.392           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.702           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.152           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.930           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.289           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.760           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.578           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.945           ms/op
ClientPb.existUser                      sample  171664   5.589 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.175           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.939           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.791           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.224           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.809           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.933           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.539           ms/op
ClientPb.getUser                        sample  169739   5.654 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.495           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.374           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.988           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.700           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.798           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.496           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.801           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.159           ms/op
ClientPb.listUser                       sample  141671   6.774 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.825           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.472           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.323           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.322           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.124           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.103           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.814           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.026           ms/op
