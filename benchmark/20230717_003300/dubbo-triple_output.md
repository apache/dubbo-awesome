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
# Warmup Iteration   1: 1.069 ops/ms
# Warmup Iteration   2: 2.325 ops/ms
# Warmup Iteration   3: 5.105 ops/ms
Iteration   1: 5.541 ops/ms
Iteration   2: 5.794 ops/ms
Iteration   3: 5.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.763 ±(99.9%) 3.814 ops/ms [Average]
  (min, avg, max) = (5.541, 5.763, 5.956), stdev = 0.209
  CI (99.9%): [1.950, 9.577] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.658 ops/ms
# Warmup Iteration   2: 4.860 ops/ms
# Warmup Iteration   3: 5.805 ops/ms
Iteration   1: 6.053 ops/ms
Iteration   2: 6.007 ops/ms
Iteration   3: 6.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.021 ±(99.9%) 0.508 ops/ms [Average]
  (min, avg, max) = (6.002, 6.021, 6.053), stdev = 0.028
  CI (99.9%): [5.512, 6.529] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.465 ops/ms
# Warmup Iteration   2: 4.045 ops/ms
# Warmup Iteration   3: 5.648 ops/ms
Iteration   1: 5.612 ops/ms
Iteration   2: 5.604 ops/ms
Iteration   3: 5.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.689 ±(99.9%) 2.552 ops/ms [Average]
  (min, avg, max) = (5.604, 5.689, 5.850), stdev = 0.140
  CI (99.9%): [3.137, 8.241] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.653 ops/ms
# Warmup Iteration   2: 4.078 ops/ms
# Warmup Iteration   3: 5.061 ops/ms
Iteration   1: 4.968 ops/ms
Iteration   2: 4.979 ops/ms
Iteration   3: 4.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.976 ±(99.9%) 0.121 ops/ms [Average]
  (min, avg, max) = (4.968, 4.976, 4.980), stdev = 0.007
  CI (99.9%): [4.855, 5.096] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 17.315 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 6.803 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.852 ±(99.9%) 0.014 ms/op
Iteration   1: 5.693 ±(99.9%) 0.010 ms/op
Iteration   2: 5.668 ±(99.9%) 0.015 ms/op
Iteration   3: 5.539 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.633 ±(99.9%) 1.512 ms/op [Average]
  (min, avg, max) = (5.539, 5.633, 5.693), stdev = 0.083
  CI (99.9%): [4.121, 7.145] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.286 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 6.188 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.504 ±(99.9%) 0.009 ms/op
Iteration   1: 5.324 ±(99.9%) 0.014 ms/op
Iteration   2: 5.261 ±(99.9%) 0.011 ms/op
Iteration   3: 5.386 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.323 ±(99.9%) 1.141 ms/op [Average]
  (min, avg, max) = (5.261, 5.323, 5.386), stdev = 0.063
  CI (99.9%): [4.182, 6.465] (assumes normal distribution)


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
# Warmup Iteration   1: 15.364 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.771 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.524 ±(99.9%) 0.013 ms/op
Iteration   1: 5.819 ±(99.9%) 0.010 ms/op
Iteration   2: 5.600 ±(99.9%) 0.012 ms/op
Iteration   3: 5.553 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.657 ±(99.9%) 2.586 ms/op [Average]
  (min, avg, max) = (5.553, 5.657, 5.819), stdev = 0.142
  CI (99.9%): [3.071, 8.243] (assumes normal distribution)


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
# Warmup Iteration   1: 19.445 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 7.432 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.440 ±(99.9%) 0.019 ms/op
Iteration   1: 6.555 ±(99.9%) 0.012 ms/op
Iteration   2: 6.277 ±(99.9%) 0.023 ms/op
Iteration   3: 6.435 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.422 ±(99.9%) 2.542 ms/op [Average]
  (min, avg, max) = (6.277, 6.422, 6.555), stdev = 0.139
  CI (99.9%): [3.880, 8.965] (assumes normal distribution)


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
# Warmup Iteration   1: 18.006 ±(99.9%) 0.328 ms/op
# Warmup Iteration   2: 6.867 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.415 ±(99.9%) 0.032 ms/op
Iteration   1: 5.658 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.290 ms/op
                 createUser·p0.50:   5.366 ms/op
                 createUser·p0.90:   7.070 ms/op
                 createUser·p0.95:   8.004 ms/op
                 createUser·p0.99:   10.422 ms/op
                 createUser·p0.999:  26.995 ms/op
                 createUser·p0.9999: 32.420 ms/op
                 createUser·p1.00:   32.932 ms/op

Iteration   2: 5.648 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.376 ms/op
                 createUser·p0.50:   5.390 ms/op
                 createUser·p0.90:   6.996 ms/op
                 createUser·p0.95:   7.700 ms/op
                 createUser·p0.99:   10.289 ms/op
                 createUser·p0.999:  25.824 ms/op
                 createUser·p0.9999: 31.293 ms/op
                 createUser·p1.00:   31.392 ms/op

Iteration   3: 5.348 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.851 ms/op
                 createUser·p0.50:   5.071 ms/op
                 createUser·p0.90:   6.562 ms/op
                 createUser·p0.95:   7.315 ms/op
                 createUser·p0.99:   9.699 ms/op
                 createUser·p0.999:  20.401 ms/op
                 createUser·p0.9999: 35.129 ms/op
                 createUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 173027
  mean =      5.548 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 62717 
    [ 5.000,  7.500) = 100317 
    [ 7.500, 10.000) = 8092 
    [10.000, 12.500) = 1425 
    [12.500, 15.000) = 217 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.851 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      6.889 ms/op
     p(95.0000) =      7.700 ms/op
     p(99.0000) =     10.158 ms/op
     p(99.9000) =     20.939 ms/op
     p(99.9900) =     33.554 ms/op
     p(99.9990) =     35.800 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 15.837 ±(99.9%) 0.236 ms/op
# Warmup Iteration   2: 6.642 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.508 ±(99.9%) 0.023 ms/op
Iteration   1: 5.378 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.769 ms/op
                 existUser·p0.50:   5.087 ms/op
                 existUser·p0.90:   6.676 ms/op
                 existUser·p0.95:   7.676 ms/op
                 existUser·p0.99:   10.942 ms/op
                 existUser·p0.999:  21.528 ms/op
                 existUser·p0.9999: 27.928 ms/op
                 existUser·p1.00:   28.770 ms/op

Iteration   2: 5.370 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.241 ms/op
                 existUser·p0.50:   5.087 ms/op
                 existUser·p0.90:   6.636 ms/op
                 existUser·p0.95:   7.373 ms/op
                 existUser·p0.99:   9.978 ms/op
                 existUser·p0.999:  26.423 ms/op
                 existUser·p0.9999: 29.035 ms/op
                 existUser·p1.00:   29.884 ms/op

Iteration   3: 5.429 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.200 ms/op
                 existUser·p0.50:   5.095 ms/op
                 existUser·p0.90:   6.914 ms/op
                 existUser·p0.95:   7.873 ms/op
                 existUser·p0.99:   10.420 ms/op
                 existUser·p0.999:  14.716 ms/op
                 existUser·p0.9999: 34.603 ms/op
                 existUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177956
  mean =      5.392 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 80046 
    [ 5.000,  7.500) = 88226 
    [ 7.500, 10.000) = 7441 
    [10.000, 12.500) = 1512 
    [12.500, 15.000) = 452 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.769 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      6.734 ms/op
     p(95.0000) =      7.635 ms/op
     p(99.0000) =     10.453 ms/op
     p(99.9000) =     17.303 ms/op
     p(99.9900) =     31.674 ms/op
     p(99.9990) =     34.974 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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
# Warmup Iteration   1: 17.717 ±(99.9%) 0.269 ms/op
# Warmup Iteration   2: 6.856 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.751 ±(99.9%) 0.023 ms/op
Iteration   1: 5.635 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.568 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   7.053 ms/op
                 getUser·p0.95:   8.602 ms/op
                 getUser·p0.99:   11.665 ms/op
                 getUser·p0.999:  24.543 ms/op
                 getUser·p0.9999: 33.281 ms/op
                 getUser·p1.00:   34.013 ms/op

Iteration   2: 5.659 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.679 ms/op
                 getUser·p0.50:   5.390 ms/op
                 getUser·p0.90:   7.021 ms/op
                 getUser·p0.95:   7.897 ms/op
                 getUser·p0.99:   9.896 ms/op
                 getUser·p0.999:  18.071 ms/op
                 getUser·p0.9999: 28.913 ms/op
                 getUser·p1.00:   31.556 ms/op

Iteration   3: 5.715 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.572 ms/op
                 getUser·p0.50:   5.472 ms/op
                 getUser·p0.90:   7.012 ms/op
                 getUser·p0.95:   7.913 ms/op
                 getUser·p0.99:   10.225 ms/op
                 getUser·p0.999:  27.657 ms/op
                 getUser·p0.9999: 30.953 ms/op
                 getUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 169238
  mean =      5.670 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 52468 
    [ 5.000,  7.500) = 104782 
    [ 7.500, 10.000) = 9479 
    [10.000, 12.500) = 1734 
    [12.500, 15.000) = 381 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.568 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      7.029 ms/op
     p(95.0000) =      8.061 ms/op
     p(99.0000) =     10.699 ms/op
     p(99.9000) =     18.768 ms/op
     p(99.9900) =     32.869 ms/op
     p(99.9990) =     33.741 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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
# Warmup Iteration   1: 21.116 ±(99.9%) 0.373 ms/op
# Warmup Iteration   2: 7.945 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.800 ±(99.9%) 0.027 ms/op
Iteration   1: 6.525 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.949 ms/op
                 listUser·p0.50:   6.267 ms/op
                 listUser·p0.90:   7.774 ms/op
                 listUser·p0.95:   8.651 ms/op
                 listUser·p0.99:   11.518 ms/op
                 listUser·p0.999:  26.736 ms/op
                 listUser·p0.9999: 32.280 ms/op
                 listUser·p1.00:   33.030 ms/op

Iteration   2: 6.525 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   6.128 ms/op
                 listUser·p0.90:   7.938 ms/op
                 listUser·p0.95:   9.077 ms/op
                 listUser·p0.99:   13.517 ms/op
                 listUser·p0.999:  28.672 ms/op
                 listUser·p0.9999: 31.631 ms/op
                 listUser·p1.00:   32.473 ms/op

Iteration   3: 6.602 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.690 ms/op
                 listUser·p0.50:   6.119 ms/op
                 listUser·p0.90:   8.249 ms/op
                 listUser·p0.95:   9.552 ms/op
                 listUser·p0.99:   13.730 ms/op
                 listUser·p0.999:  29.098 ms/op
                 listUser·p0.9999: 36.862 ms/op
                 listUser·p1.00:   39.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 146479
  mean =      6.550 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 4668 
    [ 5.000,  7.500) = 120617 
    [ 7.500, 10.000) = 16562 
    [10.000, 12.500) = 2954 
    [12.500, 15.000) = 955 
    [15.000, 17.500) = 310 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.690 ms/op
     p(50.0000) =      6.177 ms/op
     p(90.0000) =      7.987 ms/op
     p(95.0000) =      9.077 ms/op
     p(99.0000) =     12.993 ms/op
     p(99.9000) =     28.296 ms/op
     p(99.9900) =     35.281 ms/op
     p(99.9990) =     39.916 ms/op
     p(99.9999) =     39.977 ms/op
    p(100.0000) =     39.977 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.763 ± 3.814  ops/ms
ClientPb.existUser                       thrpt       3   6.021 ± 0.508  ops/ms
ClientPb.getUser                         thrpt       3   5.689 ± 2.552  ops/ms
ClientPb.listUser                        thrpt       3   4.976 ± 0.121  ops/ms
ClientPb.createUser                       avgt       3   5.633 ± 1.512   ms/op
ClientPb.existUser                        avgt       3   5.323 ± 1.141   ms/op
ClientPb.getUser                          avgt       3   5.657 ± 2.586   ms/op
ClientPb.listUser                         avgt       3   6.422 ± 2.542   ms/op
ClientPb.createUser                     sample  173027   5.548 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.851           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.259           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.889           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.700           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.158           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.939           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.554           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.848           ms/op
ClientPb.existUser                      sample  177956   5.392 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.769           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.087           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.734           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.635           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.453           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.303           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.674           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.127           ms/op
ClientPb.getUser                        sample  169238   5.670 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.374           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.029           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.061           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.699           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.768           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.869           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.013           ms/op
ClientPb.listUser                       sample  146479   6.550 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.690           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.177           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.987           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.077           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.993           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.296           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.281           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.977           ms/op
