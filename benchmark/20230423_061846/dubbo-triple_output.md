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
# Warmup Iteration   1: 1.533 ops/ms
# Warmup Iteration   2: 3.547 ops/ms
# Warmup Iteration   3: 6.994 ops/ms
Iteration   1: 7.526 ops/ms
Iteration   2: 7.826 ops/ms
Iteration   3: 7.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.686 ±(99.9%) 2.750 ops/ms [Average]
  (min, avg, max) = (7.526, 7.686, 7.826), stdev = 0.151
  CI (99.9%): [4.936, 10.436] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.241 ops/ms
# Warmup Iteration   2: 6.204 ops/ms
# Warmup Iteration   3: 8.073 ops/ms
Iteration   1: 8.482 ops/ms
Iteration   2: 8.502 ops/ms
Iteration   3: 8.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.536 ±(99.9%) 1.409 ops/ms [Average]
  (min, avg, max) = (8.482, 8.536, 8.624), stdev = 0.077
  CI (99.9%): [7.127, 9.945] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.401 ops/ms
# Warmup Iteration   2: 6.720 ops/ms
# Warmup Iteration   3: 7.563 ops/ms
Iteration   1: 8.221 ops/ms
Iteration   2: 8.171 ops/ms
Iteration   3: 8.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.199 ±(99.9%) 0.470 ops/ms [Average]
  (min, avg, max) = (8.171, 8.199, 8.221), stdev = 0.026
  CI (99.9%): [7.729, 8.669] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.073 ops/ms
# Warmup Iteration   2: 5.742 ops/ms
# Warmup Iteration   3: 6.998 ops/ms
Iteration   1: 6.548 ops/ms
Iteration   2: 6.859 ops/ms
Iteration   3: 7.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.816 ±(99.9%) 4.534 ops/ms [Average]
  (min, avg, max) = (6.548, 6.816, 7.040), stdev = 0.249
  CI (99.9%): [2.282, 11.350] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.560 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.154 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.360 ±(99.9%) 0.005 ms/op
Iteration   1: 4.026 ±(99.9%) 0.010 ms/op
Iteration   2: 4.223 ±(99.9%) 0.009 ms/op
Iteration   3: 3.964 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.071 ±(99.9%) 2.468 ms/op [Average]
  (min, avg, max) = (3.964, 4.071, 4.223), stdev = 0.135
  CI (99.9%): [1.603, 6.539] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 10.252 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.292 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.005 ms/op
Iteration   1: 3.827 ±(99.9%) 0.008 ms/op
Iteration   2: 3.880 ±(99.9%) 0.005 ms/op
Iteration   3: 3.765 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.824 ±(99.9%) 1.047 ms/op [Average]
  (min, avg, max) = (3.765, 3.824, 3.880), stdev = 0.057
  CI (99.9%): [2.777, 4.871] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.668 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.564 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.223 ±(99.9%) 0.005 ms/op
Iteration   1: 3.980 ±(99.9%) 0.010 ms/op
Iteration   2: 3.892 ±(99.9%) 0.009 ms/op
Iteration   3: 4.014 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.962 ±(99.9%) 1.151 ms/op [Average]
  (min, avg, max) = (3.892, 3.962, 4.014), stdev = 0.063
  CI (99.9%): [2.811, 5.112] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 15.218 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.667 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.721 ±(99.9%) 0.010 ms/op
Iteration   1: 4.663 ±(99.9%) 0.011 ms/op
Iteration   2: 4.838 ±(99.9%) 0.010 ms/op
Iteration   3: 4.528 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.676 ±(99.9%) 2.835 ms/op [Average]
  (min, avg, max) = (4.528, 4.676, 4.838), stdev = 0.155
  CI (99.9%): [1.841, 7.511] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.658 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.901 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.356 ±(99.9%) 0.017 ms/op
Iteration   1: 3.908 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.788 ms/op
                 createUser·p0.50:   3.736 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   7.176 ms/op
                 createUser·p0.999:  24.117 ms/op
                 createUser·p0.9999: 26.274 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   2: 3.878 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   6.423 ms/op
                 createUser·p0.999:  25.700 ms/op
                 createUser·p0.9999: 28.795 ms/op
                 createUser·p1.00:   30.638 ms/op

Iteration   3: 3.940 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.066 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.735 ms/op
                 createUser·p0.999:  11.828 ms/op
                 createUser·p0.9999: 34.727 ms/op
                 createUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 245469
  mean =      3.909 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 321 
    [ 2.500,  5.000) = 237485 
    [ 5.000,  7.500) = 5921 
    [ 7.500, 10.000) = 1201 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 127 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     24.052 ms/op
     p(99.9900) =     32.801 ms/op
     p(99.9990) =     35.789 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 12.482 ±(99.9%) 0.206 ms/op
# Warmup Iteration   2: 4.306 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.011 ms/op
Iteration   1: 3.856 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.597 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   6.652 ms/op
                 existUser·p0.999:  24.445 ms/op
                 existUser·p0.9999: 27.801 ms/op
                 existUser·p1.00:   28.443 ms/op

Iteration   2: 3.999 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.479 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.702 ms/op
                 existUser·p0.95:   5.235 ms/op
                 existUser·p0.99:   7.086 ms/op
                 existUser·p0.999:  10.273 ms/op
                 existUser·p0.9999: 32.932 ms/op
                 existUser·p1.00:   35.324 ms/op

Iteration   3: 3.906 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.303 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   6.865 ms/op
                 existUser·p0.999:  27.104 ms/op
                 existUser·p0.9999: 30.462 ms/op
                 existUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244751
  mean =      3.920 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 337 
    [ 2.500,  5.000) = 233539 
    [ 5.000,  7.500) = 9040 
    [ 7.500, 10.000) = 1173 
    [10.000, 12.500) = 357 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     24.289 ms/op
     p(99.9900) =     30.802 ms/op
     p(99.9990) =     34.070 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.549 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.705 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.202 ±(99.9%) 0.015 ms/op
Iteration   1: 4.077 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.154 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   6.423 ms/op
                 getUser·p0.99:   9.328 ms/op
                 getUser·p0.999:  23.298 ms/op
                 getUser·p0.9999: 29.061 ms/op
                 getUser·p1.00:   30.769 ms/op

Iteration   2: 4.110 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.493 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   4.784 ms/op
                 getUser·p0.95:   5.210 ms/op
                 getUser·p0.99:   7.525 ms/op
                 getUser·p0.999:  24.289 ms/op
                 getUser·p0.9999: 26.717 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   3: 4.036 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.581 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  11.646 ms/op
                 getUser·p0.9999: 28.707 ms/op
                 getUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235503
  mean =      4.074 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 222452 
    [ 5.000,  7.500) = 8948 
    [ 7.500, 10.000) = 3040 
    [10.000, 12.500) = 627 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 123 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.493 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      8.421 ms/op
     p(99.9000) =     23.183 ms/op
     p(99.9900) =     28.541 ms/op
     p(99.9990) =     30.285 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


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
# Warmup Iteration   1: 15.035 ±(99.9%) 0.210 ms/op
# Warmup Iteration   2: 5.431 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.624 ±(99.9%) 0.015 ms/op
Iteration   1: 4.821 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  27.623 ms/op
                 listUser·p0.9999: 40.656 ms/op
                 listUser·p1.00:   42.009 ms/op

Iteration   2: 4.730 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.519 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   8.847 ms/op
                 listUser·p0.999:  18.691 ms/op
                 listUser·p0.9999: 24.417 ms/op
                 listUser·p1.00:   25.133 ms/op

Iteration   3: 4.658 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.087 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.692 ms/op
                 listUser·p0.99:   8.126 ms/op
                 listUser·p0.999:  15.106 ms/op
                 listUser·p0.9999: 18.305 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202537
  mean =      4.735 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 170502 
    [ 5.000, 10.000) = 31003 
    [10.000, 15.000) = 660 
    [15.000, 20.000) = 195 
    [20.000, 25.000) = 77 
    [25.000, 30.000) = 62 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 22 

  Percentiles, ms/op:
      p(0.0000) =      2.087 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     40.108 ms/op
     p(99.9990) =     41.804 ms/op
     p(99.9999) =     42.009 ms/op
    p(100.0000) =     42.009 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.686 ± 2.750  ops/ms
ClientPb.existUser                       thrpt       3   8.536 ± 1.409  ops/ms
ClientPb.getUser                         thrpt       3   8.199 ± 0.470  ops/ms
ClientPb.listUser                        thrpt       3   6.816 ± 4.534  ops/ms
ClientPb.createUser                       avgt       3   4.071 ± 2.468   ms/op
ClientPb.existUser                        avgt       3   3.824 ± 1.047   ms/op
ClientPb.getUser                          avgt       3   3.962 ± 1.151   ms/op
ClientPb.listUser                         avgt       3   4.676 ± 2.835   ms/op
ClientPb.createUser                     sample  245469   3.909 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.034           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.756           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.399           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.052           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.801           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.979           ms/op
ClientPb.existUser                      sample  244751   3.920 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.303           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.785           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.465           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.907           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.922           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.289           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.802           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.324           ms/op
ClientPb.getUser                        sample  235503   4.074 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.493           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.579           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.112           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.421           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.183           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.541           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.769           ms/op
ClientPb.listUser                       sample  202537   4.735 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.087           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.716           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.678           ms/op
ClientPb.listUser:listUser·p0.9999      sample          40.108           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.009           ms/op
